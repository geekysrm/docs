.. _hasura_conf_generate-domain:

hasura conf generate-domain
---------------------------

Generate a domain configuration for a cluster

Synopsis
~~~~~~~~


Generate a domain configuration that has to be added to domains.yaml configuration to update the clusters domain

::

  hasura conf generate-domain [domain-name] [flags]

Examples
~~~~~~~~

::

  # To add domains to your cluster:
  $ hasura conf generate-domain example.com -c hasura

Options
~~~~~~~

::

  -c, --cluster string   name of the cluster to be contacted
  -h, --help             help for generate-domain

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --project string   hasura project directory where the commands should be executed. (default: current directory)

SEE ALSO
~~~~~~~~

* :ref:`hasura conf <hasura_conf>` 	 - Manage configuration on the cluster

*Auto generated by spf13/cobra on 23-Nov-2017*
