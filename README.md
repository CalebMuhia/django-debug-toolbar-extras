django-debug-toolbar-extras
===========================

This is a collection of add-on panels to django-debug-toolbar.

Currently there are the following panels:

 * URLconf - for displaying a panel of the urlconf for the current request.


Requirements
------------

 * django (any version which supports django-debug-toolbar should work)
 * django-debug-toolbar (tested with 0.9.0-dev)


Installation
------------

Add debug_toolbar_extras to your INSTALLED_APPS:

    INSTALLED_APPS = (
        ...
        'debug_toolbar',
        'debug_toolar_extras',
    )

    DEBUG_TOOLBAR_PANELS = (
        ...
        'debug_toolbar_extras.panels.urlconf.URLconfDebugPanel',
        ...
    )
