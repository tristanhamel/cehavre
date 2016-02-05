# cehavre
*A map blogging platform*

##WARNING
This repository is provided for documentation only in order to showcase code samples in non minified format.
The project the code was written for is still running --> [Ce Havre qui t'appelle](https://cehavrequitappelle.fr).
Some files containing sensitive data are not provided and neither is the wordpress folder.

##Some remarks on the structure of the code.
The application is based on AngularJs 1.4 and Foundation 5. All the data is handled via a wordpress installation.
Communication bewteen the Wordpress install and the frontend app is achieved with Restful API leveraging the benefits of the brandnew Wordpress REST api (via plugin).

In addition of the various parts of the Angular app, this repository includes various php files used in a completely custom wordpress theme.
The application also makes use of custom REST endpoints (see in src/plugin).

The gulp file contains tasks such as watch, dist and dependency injection.
