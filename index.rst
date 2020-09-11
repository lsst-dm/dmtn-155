..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

Introduction
============

The Data Management team currently provides excellent support to our community of science pipelines users, and that community is starting to expand rapidly.
The community support system for Rubin Operations must be scalable and sustainable, and capable of serving an active user community of thousands of people with a wide variety of skills, background, expertise, and resources.

This tech note provides an interim support model as a stepping-stone to the future system.
The main goals of this interim model are to reduce barriers to accessing information and participating in Rubin science, and to enable crowd-sourced problem solving.
We aim to achieve those goals by building a deep repository of openly available and searchable expertise and cultivating a global community of engaged scientists. 

For these reasons, the interim support model emphasizes use of the Community Forum for all interactions between DM staff and the science community, instead of Slack or email.

This interim model has three main components:

#. DM staff are encouraged to post questions and answers related to community support in the Community Forum as often as possible, and to encourage the user community to do the same.
#. The DM System Science Team (SST) will monitor the "Support" category on Community to ensure no question gets left behind.
#. DM staff are encouraged to use the ``#dm-support`` Slack channel, which is linked directly to the Community Forum, to discuss Forum postings and coordinate responses.

The intended result is that the Community Forum grows to host a reservoir of accessible Rubin-related expertise and serve as a resource for open and engaging interactions between all members of the broad Rubin community.

.. Add content here.

Redirecting Questions to the Community Forum
============================================

It is appreciated that redirecting user questions that come by email or Slack message to the Community Forum could be socially awkward, especially during this interim time when usage of Community.lsst.org is still ramping up.
Below are several phrases that we can all use to help us engage users in the Community Forum.
Which of these phrases you might choose to use, and how much additional information that you supply, will of course depend on the situation.
(E.g., links to the Forum categories, existing topics, or instructions; expressions of gratitude like "great question!" or "thanks so much!").

 - "To make sure the answer can help others as well, I have posted my answer in the X category at Community.lsst.org. Please do feel free to reply in that thread with any follow-up questions on this topic."
 - "It is DM's policy that we answer questions in the open public forum at Community.lsst.org; would you mind posting your question as a new Topic in the X category?"
 - "To make sure this question is fully answered by the relevant DM staff members, could you please post it as a new topic in the X category at Community.lsst.org?"
 - "I think this topic at Community.lsst.org contains the answer to your question?"


Linking users to the appropriate category in the Community Forum.
-----------------------------------------------------------------

Most questions that DM staff recieve from the user community will be appropriate for categories **Science - Data Q&A** or **Support**.

**Science - Data Q&A**: https://community.lsst.org/c/sci/data/

Primarily used for questions about the planned data products (e.g., scientific applications).
This category is monitored by the DM-SST to ensure all questions recieve timely answers.

**Support**: https://community.lsst.org/c/support/

Primarily used for questions about applications of the science pipelines (e.g., errors returned during attempts to process data from other facilities).
This category is monitored by DM team members, and all new posts appear in the LSSTC Slack channel `#dm-support` to help us coordinate responses.

As a side note, there is a category for Data Management, but in most cases it would be inappropriate to direct a user to this category.
This category is primarily used for discussion about the development of the science pipelines, and most of its sub-categories are private (visible only to Project staff).


Linking users to information about the Community Forum.
-------------------------------------------------------

Users will need an account for Community.lsst.org in order to post, but all public content is visible without an account.

If users have questions about Community.lsst.org, direct them to the Meta_ category.

.. _Meta: https://community.lsst.org/c/meta/

Here are some quick links to Meta topics for anticipated FAQs:

 - subscrbing via RSS_ or email_
 - `using GitHub authentication`_
 - `saving draft posts`_
 - `tips for replying to topics`_
 - `formatting math and code`_
 - `understanding flat threading`_

.. _`saving draft posts`: https://community.lsst.org/t/can-i-save-a-draft-post-and-finish-it-later/4308
.. _`tips for replying to topics`: https://community.lsst.org/t/tips-for-effective-conversation-on-the-forum-replies-quotes-and-replying-as-a-new-topic/1273
.. _RSS: https://community.lsst.org/t/how-to-subscribe-via-rss/41
.. _email: https://community.lsst.org/t/how-to-subscribe-to-emails-of-all-new-topics-in-categories-or-tags/37
.. _`understanding flat threading`: https://community.lsst.org/t/understanding-and-using-discourses-flat-threading/150
.. _`using GitHub authentication`: https://community.lsst.org/t/how-do-i-login-using-github-authentication-instead-of-a-password/31
.. _`formatting math and code`: https://community.lsst.org/t/how-to-format-posts-including-math-and-code/38

Additionally, a "tour" of Community.lsst.org was provided during the Rubin 2020 PCW session on Community Support.
The tour starts at 25 minutes and 45 seconds into `the recorded presentation`_.
More information about that session is available in `this Community Forum topic`_.

.. _`the recorded presentation`: https://www.youtube.com/watch?v=HJQSHc7qcGE&feature=youtu.be
.. _`this Community Forum topic`: https://community.lsst.org/t/rubin-pcw-2020-community-support-for-science/4344


Cases in which the Community Forum might not be used.
-----------------------------------------------------

The Community Forum is open and publicly accessible.
Rare cases involving detailed questions about the science pipelines performance on proprietary data might be inappropriate to post if the question includes data or images or could reveal a potential scientific result.
The first response should be to try and "anonymize" the question so that it can be posted to Community without revealing any proprietary data.
However, if this cannot be done then the user should be accommodated and interaction should proceed privately.

Slack should continue to be used as a discussion forum during live events related to community support, such as workshops or tutorials.
Good examples of Slack used in this context include the ``#stack-club-course`` channel for real-time support during the `Stack Club Course`_ from May through August of 2020.

.. _`Stack Club Course`: \url{https://github.com/LSSTScienceCollaborations/StackClubCourse



JIRA for DM Staff
=================

There will be cases where difficult questions are posted to the Community Forum, or the ensuing discussions reveal bugs or desired new features.
These cases might require scheduled work on behalf of DM staff to generate an answer.
This work should be done with JIRA tickets to ensure it is trackable and accounted for.
All DM staff should be sure to talk to their T/CAM if a support-related activity requires such work.


Documentation
=============

This Tech Note is focused on dynamic modes of community support (e.g., providing explanations, answering questions), but static modes (e.g., tutorials, documentation, and the pipelines code itself) remain a very important and efficient component of DM's community support.
These aspects of DM community support are already well described in `the DM Developer Guide`_.

.. _`the DM Developer Guide`: https://developer.lsst.io


Community Engagement Team
=========================

The Rubin Observatory Community Engagement Team (CET) within the System Performance department will be responsible for facilitating support for science users of Rubin data products and services during Operations.
The full model for community support during operations will be described in `RTN-00X`_.
Pre-operations CET members will help to monitor postings to the Community Forum categories "Support" and "Science - Data Q&A", and assist when possible with responding to questions.
They will also be evaluating the effectiveness of this interim model in achieving its goals, and soliciting feedback about communications tools from both DM and the science community, to inform their plans for a community support model during Operations.

.. _RTN-00X: tbd





.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa