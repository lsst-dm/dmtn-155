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

To date, the Rubin Data Management team has provided excellent informal and ad-hoc support to our early-adopter community of science pipelines and science platform users.
This support, mostly via Slack ``#dm-*`` channels, and on occassion via the Community.lsst.org forum, has been on a best effort basis;  Data Management is not scoped to provide community support in construction.  
As we move into pre-operations, with its program of Data Previews, and eventually into full operations, this user community will expand rapidly, and so too will the demand for support.  
The current best-effort support provided by the DM team will not scale. 

In Operations, community support for science is the responsibility of the Community Engagement Team (see :ref:`cet`). 
The community support model for Rubin Operations must be scalable, sustainable, and capable of serving an active user community of thousands of people with a wide variety of skills, background, expertise, and resources. 
We aim to achieve these goals by building a deep repository of openly available and searchable knowledge, and cultivating a global community of engaged scientists to crowd source problem solving. 

This tech note provides an interim support model as a stepping-stone towards this future operations-era model.
Its goal is to provide guidelines for the DM team in supporting and responding to questions from  the community in construction, and to  transition from the current informal and ad-hoc support provided via Slack, to the more sustainable model envisaged in operations. 

Interim Support Model
=====================

The interim support model emphasizes use of the Community Forum for all interactions between DM staff and the science community, instead of Slack or email.

This interim model has two main components:

#. DM staff are requested to not respond to emails or slack messages, either direct or to `dm-*` channels requesting support, but rather redirect questions to the Community.lsst.org forum.
#. The DM System Science Team (SST) will monitor the "Support" category Community in a best effort to ensure all inquiries are acknowledged, and answered when possible.

The intended result is that the Community Forum grows to host a repository of accessible Rubin-related expertise and serve as a resource for open and engaging interactions between all members of the broad Rubin community.

Towards this end, it would be helpful for staff to post internal questions and answers related to use of the LSST science pipelines and Rubin science platform in the Community Forum as often as possible (as preemptive community support). 
As is the case now, there is no expectation that DM staff provide answers for questions they recieve, but may continue providing support on a best effort basis as their time allows, with development work on the Rubin science pipelines remaining the priority of the construction team.
DM staff participating in community support are encouraged to use the ``#dm-support`` Slack channel, which is linked directly to the Community Forum, to discuss Forum postings and coordinate responses.


Redirecting Questions to the Community Forum
============================================

It is appreciated that redirecting user questions that come by email or Slack message to the Community Forum could be socially awkward, especially during this interim time when usage of Community.lsst.org is still ramping up.
Below are several phrases that we can all use to help us engage users in the Community Forum.
Which of these phrases you might choose to use, and how much additional information that you supply, will of course depend on the nature of the question and its potential answer.

- You know the answer and will provide it.
  - "I'm sure I can answer this question for you, but it is DM's policy that we answer questions in the open public forum at Community.lsst.org. Would you mind posting your question as a new topic in the Support category, so that I can answer it there?"
  - "To make sure the answer can help others as well, I have posted this question and my answer in the Support category at Community.lsst.org. Please do feel free to reply in that thread with any follow-up questions on this topic."

- You don't know the answer or will not provide the answer.
  - "Unfortunately, I don't know the answer off the top of my head. Could you please post it as a new topic in the Support category at Community.lsst.org? Hopefully someone there will be familiar with this issue."
  - "I'm not sure what the answer is, but this question would be perfect for the Support category at Community.lsst.org. Please try posting in there as a new topic?"
  - As a side note, if you think a particular DM staff member has the answer, please ask them privately or in the ``#dm-support`` Slack channel if they are interested in responding, instead of mentioning them publicly on Community.

Along with the redirect to Community, it might also be appropriate to supply direct links to a Forum category or existing topics (see below), and of course personal expressions like "great question!" or "thanks so much" are at your discretion.


Linking users to the appropriate category in the Community Forum.
-----------------------------------------------------------------

Most questions that DM staff recieve from the user community will be appropriate for categories **Science - Data Q&A** or **Support**.

**Science - Data Q&A**: https://community.lsst.org/c/sci/data/

Primarily used for questions about the planned data products (e.g., scientific applications).
This category is monitored by the DM-SST to ensure all questions recieve timely answers.

**Support**: https://community.lsst.org/c/support/ 

Primarily used for questions about applications of the science pipelines (e.g., errors returned during attempts to process data from other facilities).


**Support  — Rubin Science Platform**: https://community.lsst.org/c/support/lsp

Support subcategory for questions relating to the Rubin Science Platform.

These categories are monitored by DM team members, and all new posts appear in the LSSTC Slack channel `#dm-support` to help us coordinate responses.


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

Slack should continue to be used as a chat platform during live events involving the community, such as workshops or tutorials where real-time communication is needed.
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

.. _cet:

Community Engagement Team
=========================

The Rubin Observatory Community Engagement Team (CET) within the System Performance department will be responsible for facilitating support for science users of Rubin data products and services during Operations.
The full model for community support during operations will be described in `RTN-006`_.
Pre-operations CET members will help to monitor postings to the Community Forum categories "Support" and "Science - Data Q&A", and assist when possible with responding to questions.
They will also be evaluating the effectiveness of this interim model in achieving its goals, and soliciting feedback about communications tools from both DM and the science community, to inform their plans for a community support model during Operations.

.. _RTN-006: https://rtn-006.lsst.io/


.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa