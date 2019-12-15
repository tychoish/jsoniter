======================================================
``jsoniter`` -- JSON Creation and Manipulation Library
======================================================

Overview
--------

This package is a fork of `json-iteration/go
<https://github.com/json-iterator/go>`_, with fewer dependencies, a
new README, and more idiomatic path. Future work may include an
additional API that more closely resembles `evergreen-ci/birch
<https://github.com/evergreen-ci/birch>`_.

Documentation
-------------

- `godoc <https://godoc.org/github.com/tychoish/jsoniter>`_
- `jsoniter.com <http://jsoniter.com/>`_ 

Future Work
-----------

At this time, the API of this package is not stable, and may be
reorganized, or renamed, in the future to support the following goals:

- Add high-level, typesafe builder API for constructing JSON documents
  programmatically, on top of stream.

- JSON object wrapper for reading and manipulating JSON object without
  needing to decode it into a struct or map.

- Separate decoding/reflection implementation from other interfaces.
