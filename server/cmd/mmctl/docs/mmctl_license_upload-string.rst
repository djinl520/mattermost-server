.. _mmctl_license_upload-string:

mmctl license upload-string
---------------------------

Upload a license from a string.

Synopsis
~~~~~~~~


Upload a license from a string. Replaces current license.

::

  mmctl license upload-string [license] [flags]

Examples
~~~~~~~~

::

   license upload-string "mylicensestring"

Options
~~~~~~~

::

  -h, --help   help for upload-string

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --config string                path to the configuration file (default "$XDG_CONFIG_HOME/mmctl/config")
      --disable-pager                disables paged output
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --insecure-tls-version         allows to use TLS versions 1.0 and 1.1
      --json                         the output format will be in json format
      --local                        allows communicating with the server through a unix socket
      --quiet                        prevent mmctl to generate output for the commands
      --strict                       will only run commands if the mmctl version matches the server one
      --suppress-warnings            disables printing warning messages

SEE ALSO
~~~~~~~~

* `mmctl license <mmctl_license.rst>`_ 	 - Licensing commands
