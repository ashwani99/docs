.. _hasura_microservice_start:

hasura microservice start
-------------------------

Start a microservice

Synopsis
~~~~~~~~


Start a microservice

::

  hasura microservice start [microservice-name] [flags]

Examples
~~~~~~~~

::

    # Start a microservice called www:
    $ hasura microservice start www

Options
~~~~~~~

::

  -c, --cluster string     alias of cluster to connect to
  -h, --help               help for start
  -n, --namespace string   namespace of the microservice (user: custom microservice, hasura: hasura microservice) (default "user")

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura microservice <hasura_microservice>` 	 - Manage microservices on hasura

*Auto generated by spf13/cobra on 13-Feb-2018*
