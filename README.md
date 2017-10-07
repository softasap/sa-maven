sa-maven
========

[![Build Status](https://travis-ci.org/softasap/sa-maven.svg?branch=master)](https://travis-ci.org/softasap/sa-maven)

Install apache maven

Example of usage:

Simple

```YAML

     - {
         role: "sa-maven"
       }


```

Advanced

```YAML

     - {
         role: "sa-maven",
         option_link_mvn_to_bin: true,

         maven_version: '3.0.4',
         maven_install_dir: /opt/maven

       }


```



Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-maven` role using the command


`
   ansible-galaxy install softasap.sa-maven
`

the role will be available in the folder `library/softasap.sa-maven`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-maven"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html
