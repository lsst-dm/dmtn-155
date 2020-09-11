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

The Data Management team currently provides excellent support to our community of science pipelines users, which is starting to expand rapidly.
This tech note provides an interim model, a stepping-stone to the future community support system during Rubin Operations which must serve an active user community of thousands of people, with a wide variety of skills, background, expertise, and resources.
The primary objective of this support model is to reduce barriers to accessing information and to participating in Rubin science by developing a system that is both scalable and sustainable.
To achieve this, the model aims to enable crowd-sourced problem solving by building a deep repository of openly available and searchable expertise, and cultivating a global community of engaged scientists.
For these reasons, the interim support model emphasizes use of the Community Forum for all interactions between DM staff and the science community, instead of the LSSTC Slack space.

This interim model has three main components:

1. DM staff are encouraged to post questions and answers related to community support in the Community Forum as often as possible, and to encourage the user community to do the same.

2. The DM System Science Team (SST) will monitor the "Support" category on Community to ensure no question gets left behind.

3. DM staff are encouraged to use the ``#dm-support`` Slack channel, which is linked directly to the Community Forum, to discuss Forum postings and coordinate responses.

The intended result is that the Community Forum grows to host a reservoir of accessible Rubin-related expertise and serve as a resource for open and engaging interactions between all members of the broad Rubin community.

.. Add content here.

Redirecting Questions to the Community Forum
============================================

It is appreciated that redirecting user questions that come by email or Slack message to the Community Forum could be socially awkward, especially during this interim time when usage of Community.lsst.org is still ramping up.
Below are several phrases that we can all use to help us engage users in the Community Forum.
Which of these phrases you might choose to use, and how much additional information that you supply will of course depend on the situation.
(E.g., links to the Forum categories, existing topics, or instructions; expressions of gratitude like "great question!" or "thanks so much!").

 - "To make sure the answer can help others as well, I have posted my answer in the X category at Community.lsst.org. Please do feel free to reply in that thread with any follow-up questions on this topic."
 - "It is DM's policy that we answer questions in the open public forum at Community.lsst.org; would you mind posting your question as a new Topic in the X category?"
 - "To make sure this question is fully answered by the relevant DM staff members, could you please post it as a new topic in the X category at Community.lsst.org?"
 - "I think this topic at Community.lsst.org contains the answer to your question?"


Linking Users to the Appropriate Community Forum Category
---------------------------------------------------------

Most questions that DM staff recieve from the user community fall into one of the following three categories.

**Science - Data Q&A**: https://community.lsst.org/c/sci/data/

Primarily questions about the planned data products (e.g., scientific applications).
This category is monitored by the DM-SST to ensure all questions recieve timely answers.

**Support**: https://community.lsst.org/c/support/

Primarily questions about applications of the science pipelines (e.g., errors returned during attempts to process data from other facilities).
This category is monitored by DM team members, and all new posts appear in the LSSTC Slack channel `#dm-support` to help us coordinate responses.

**Data Management**: https://community.lsst.org/c/dm/

Primarily questions and discussion about the development of the science pipelines.



Linking Users to Information About the Community Forum
------------------------------------------------------

*E.g., how to get account, Meta posts on how to make a topic.*



Questions Involving Proprietary Data
------------------------------------

The Community Forum is open and publicly accessible.
Rare cases involving detailed questions about the science pipelines performance on proprietary data might be inappropriate to post if the question includes data or images or could reveal a potential scientific result.
The first response should be to try and "anonymize" the question so that it can be posted to Community without revealing any proprietary data.
However, if this cannot be done, then the user should be accommodated and interaction should proceed privately.



JIRA for DM Staff
=================

There will be cases where difficult questions are posted to the Community Forum, or the ensuing discussions reveal bugs or desired new features.
These cases might require scheduled work on behalf of DM staff to generate an answer.
This work should be done with JIRA tickets to ensure it is trackable and accounted for.
All DM staff should be sure to talk to their T/CAM if a support-related activity requires such work.


Documentation
=============

This Tech Note is focused on dynamic modes of community support (e.g., providing explanations, answering questions), but static modes (e.g., tutorials, documentation, and the pipelines code itself) remain a very important and efficient component of DM's community support.
These aspects of DM community support are already well described in the DM Developer Guide, `here`_.

.. _here: https://developer.lsst.io


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