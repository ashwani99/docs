.. _hasura-project-directory-microservices:


microservices/
==============

Everything regarding the microservices you add to the project is kept here. Each microservice is a directory containing a ``k8s.yaml`` file which holds the Kubernetes objects required for it and a ``src`` directory with a ``Dockerfile``, if continuous integration is configured.

``k8s.yaml`` can also be templated.

Use :ref:`hasura microservice create <hasura_microservice_create>` to create a new microservice.

.. toctree::

   */k8s.yaml <k8s.yaml.rst>
   */Dockerfile <dockerfile.rst>
