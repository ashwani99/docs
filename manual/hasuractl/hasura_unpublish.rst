.. _hasura_unpublish:

hasura unpublish
----------------

Delete from Hasura Hub

Synopsis
~~~~~~~~


Delete a project from Hasura Hub

::

  hasura unpublish [flags]

Examples
~~~~~~~~

::


    # Unpublish all versions of current hasura project:
    $ hasura unpublish

    # Unpublish particular version of current hasura project:
    $ hasura unpublish --version <version>
      

Options
~~~~~~~

::

  -h, --help             help for unpublish
      --version string   project version to unpublish

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura <hasura>` 	 - hasura controls the hasura project

*Auto generated by spf13/cobra on 13-Feb-2018*
