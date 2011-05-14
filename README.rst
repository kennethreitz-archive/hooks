Hooks: Blocking Events and Callbacks (for Python)
=================================================

Sometimes, while working with a deeply nested Application or Framework,
an event pattern can be extremely useful.

::

    import hooks

    hooks.register('channel', callback_func())
    hooks.ping('channel', args_to_pass_to_callback)
