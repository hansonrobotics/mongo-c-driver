:man_page: mongoc_client_session_t
:tags: session

mongoc_client_session_t
=======================

Use a session for a sequence of operations, optionally with causal consistency.

Synopsis
--------

.. include:: includes/session-lifecycle.txt

Example
-------

.. literalinclude:: ../examples/example-session.c
   :language: c
   :caption: example-session.c

.. only:: html

  Functions
  ---------

  .. toctree::
    :titlesonly:
    :maxdepth: 1

    mongoc_client_session_append
    mongoc_client_session_get_client
    mongoc_client_session_get_opts
    mongoc_client_session_get_lsid
    mongoc_client_session_destroy
