.. _hasura_secret_list:

hasura secret list
------------------

List secrets from a cluster

Synopsis
~~~~~~~~


List out all secrets present in the cluster

::

  hasura secret list [flags]

Examples
~~~~~~~~

::

    # To list all the secrets for the cluster:
    $ hasura secrets list -c hasura

Options
~~~~~~~

::

  -c, --cluster string   alias of the cluster to be contacted
  -h, --help             help for list

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura secret <hasura_secret>` 	 - Manage secrets on a cluster

*Auto generated by spf13/cobra on 13-Feb-2018*
