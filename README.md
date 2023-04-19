Maven Multi-Module Project

This project is an example of a multi-module project using Maven. The project consists of several modules, which are described below.

Parent Module

The parent module is the parent of all modules in the project. It contains Maven configuration and definitions of dependency versions used by individual modules.

bom-module

The bom-module contains the definition of common dependencies for all modules in the project. This avoids code duplication and ensures consistency of dependency versions.

Delivery Module

The delivery module is a multi-module project that contains three submodules: domain, infrastructure, and application. The domain module contains data models, the infrastructure module contains data access layer, and the application module contains business logic and presentation layer.

Delivery Administration Module

The delivery-administration module is a multi-module project that contains three submodules: domain, infrastructure, and application. The domain module contains data models, the infrastructure module contains data access layer, and the application module contains business logic and presentation layer. This module is used for managing deliveries.

Common Module

The common-module contains a set of common functionalities used by other modules in the project. This avoids code duplication and ensures functional consistency.

Integration Module

The integration-module contains the definition of future integrations with external systems. This module enables easy addition of new integrations and ensures consistency between them.


