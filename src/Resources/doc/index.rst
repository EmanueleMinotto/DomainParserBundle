Installation
============

Step 1: Download the Bundle
---------------------------

Open a command console, enter your project directory and execute the
following command to download the latest stable version of this bundle:

.. code-block:: bash

    $ composer require emanueleminotto/domain-parser-bundle

This command requires you to have Composer installed globally, as explained
in the `installation chapter`_ of the Composer documentation.

Step 2: Enable the Bundle
-------------------------

Then, enable the bundle by adding it to the list of registered bundles
in the ``app/AppKernel.php`` file of your project:

.. code-block:: php

    <?php
    // app/AppKernel.php

    // ...
    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                // ...

                new EmanueleMinotto\DomainParserBundle\DomainParserBundle(),
            );

            // ...
        }

        // ...
    }

Readings
--------

- `Cache Warmer`_
- `Configuration Reference`_
- `Console Commands`_
- `Twig Extension`_
- `Validator Constraints`_

.. _`installation chapter`: https://getcomposer.org/doc/00-intro.md
.. _`Cache Warmer`: https://github.com/EmanueleMinotto/DomainParserBundle/tree/master/src/Resources/doc/cache-warmer.rst
.. _`Configuration Reference`: https://github.com/EmanueleMinotto/DomainParserBundle/tree/master/src/Resources/doc/configuration-reference.rst
.. _`Console Commands`: https://github.com/EmanueleMinotto/DomainParserBundle/tree/master/src/Resources/doc/console-commands.rst
.. _`Twig Extension`: https://github.com/EmanueleMinotto/DomainParserBundle/tree/master/src/Resources/doc/twig-extension.rst
.. _`Validator Constraints`: https://github.com/EmanueleMinotto/DomainParserBundle/tree/master/src/Resources/doc/validator-constraints.rst
