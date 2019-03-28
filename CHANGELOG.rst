Change Log
==========

[0.5.8] - xxxxxx
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- changed: ensure compatibility with Core 0.13.x

[0.5.6] - xxxxxx
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- Fixed: missing input_channel in handle_message_with_tracker
- Debug logs when substituting intents


[0.5.2] - 2018-11-09
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Added
-----
- Fetch rules from server
- Optional slot containing parse_data in disambiguation and fallback policy

Changed
-------

Removed
-------

[0.5.1] - 2018-11-01
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Added
-----
- Compatibility with Rasa Core 0.11.x

Changed
-------

Removed
-------
- Webchat channel (use Rasa Core SocketIOInput instead)
- Automated tests (use Rasa Core evaluation instead)

[0.4.3] - 2018-08-14
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


Added
-----

- Fallback policy

Changed
-------

- Disambiguation and fallback policy rule syntax

[0.4.0] - 2018-08-11
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


Added
-----

- Compatibility with Rasa Core 0.10.x

Changed
-------

- Intent substitution rules are applied in sequence. When one rule is applied for a parse_data instance, remaining rules are ignored

Removed
-------

Fixed
-------

[0.3.3] - 2018-07-24
^^^^^^^^^^^^^^^^^^^^^

Added
-----
- Disambiguation

