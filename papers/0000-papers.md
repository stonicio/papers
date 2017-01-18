> status: draft

# Paper 0 — Stonic Papers

Stonic Papers are the documents to define the Stonic Project requirements, behavior and goals.

Stonic Papers are being stored in [the git repository](https://github.com/stonicio/papers) and are available online as the [browsable web site](http://papers.stonic.io/).

Every Stonic Paper MUST have the following:

* an identification number
* a human readable title
* one of the possible statuses

## Identification number

A Stonic Paper has its Identification Number assigned once and forever.

An Identification Number is being assigned by Stonic Project core team.

## Human readable title

A Stonic Paper's Title MUST be unique and reflect the main purpose of a Paper.

A Stonic Paper's Title SHOULD NOT change over time except it needs improvement or any corrections regarding a Paper's content updates.

## Paper Statuses

The current status of a Stonic Paper MUST be defined on the Paper top via `>` aka note syntax.

The list of the possible Stonic Paper Statuses:

* **wip** - work in progress.  
  A Paper is not ready for any kind of a review or a discussion.
* **draft**  
  A Paper is under a review and/or a discussion. Any comments on Papers in this status are highly appreciated.
* **rejected**  
  A Paper is finally rejected. It is allowed to submit a new Paper with an alternative proposition and/or solution.
* **accepted**  
  A Paper is finally accepted. There SHOULD be an issue opened on an implementation.
* **implemented**  
  An implementation is released. There MUST be Stonic Project component and its version provided at the top of the Paper.
