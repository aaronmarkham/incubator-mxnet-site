Python Tutorials
=====

Getting started
---------------

.. container:: cards

   .. card::
      :title: A 60-minute Gluon crash course
      :link: getting-started/crash-course/index.html

      A quick overview of the core concepts of MXNet using the Gluon API.

   .. card::
      :title: Moving from other frameworks
      :link: getting-started/to-mxnet/index.html

      Guides that ease your transition to MXNet from other framework.


Packages & Modules
------------------

.. container:: cards

   .. card::
      :title: Gluon
      :link: packages/gluon/index.html

      MXNet's imperative interface for Python. If you're new to MXNet, start here!

   .. card::
      :title: NDArray API
      :link: packages/ndarray/index.html

      How to use the NDArray API to manipulate data.
      A useful set of tutorials for beginners.

   .. card::
      :title: Symbol API
      :link: packages/symbol/index.html

      How to use MXNet's Symbol API.

   .. card::
      :title: Autograd API
      :link: packages/autograd/autograd.html

      How to use Automatic Differentiation with the Autograd API.



Performance
-----------
.. container:: cards

   .. card::
      :title: Improving Performance
      :link: performance/index.html

      How to get the best performance from MXNet.

   .. card::
      :title: Profiler
      :link: performance/backend/profiler.html

      How to profile MXNet models.

   .. card::
      :title: Compression: int8
      :link: performance/int8.html

      How to use int8 in your model to boost training speed.

   .. card::
      :title: MKL-DNN
      :link: performance/backend/mkl-dnn.html

      How to get the most from your CPU by using Intel's MKL-DNN.

   .. card::
      :title: TVM
      :link: performance/backend/tvm.html

      How to use TVM to boost performance.


Deployment
----------
.. container:: cards

   .. card::
      :title: MXNet on EC2
      :link: deploy/run-on-aws/use_ec2.html

      How to deploy MXNet on an Amazon EC2 instance.

   .. card::
      :title: MXNet on SageMaker
      :link: deploy/run-on-aws/use_sagemaker.html

      How to run MXNet using Amazon SageMaker.

      ..
         PLACEHOLDER
         .. card::
            :title: Export
            :link: deploy/export/index.html

            How to export MXNet models.

         .. card::
            :title: C++
            :link: deploy/inference/cpp.html

            How to use MXNet models in a C++ environment.

         .. card::
            :title: Scala and Java
            :link: deploy/inference/scala.html

            How to use MXNet models in a Scala or Java environment.

         PLACEHOLDER
      ..


Customization
-------------
.. container:: cards

Coming Soon (CustomOps and Custom Operators)

Next steps
----------

- To learn more about using MXNet to implement various deep learning algorithms
  from scratch, we recommend the `Dive into Deep Learning
  <https://d2l.ai>`_ book.

- Check out the `API Reference docs <../api/index.html>`_.

.. raw:: html

   <style> h1 {display: none;} </style>
   <style>.localtoc { display: none; }</style>


.. toctree::
   :hidden:
   :maxdepth: 3

   getting-started/index
   packages/index
   performance/index
   deploy/index
   extend/index