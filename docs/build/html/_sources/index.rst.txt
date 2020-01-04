.. Nest.js Of Node.js translate documentation master file, created by
   sphinx-quickstart on Mon Jan  7 17:01:40 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

효율적이고 확장 가능한 Node.js기반 서버 프레임워크
=====================================================

해당 문서는 nestjs_ **6.12.2 버전** 기준으로 작성된 문서입니다.

* 번역자: 박정태_

* 저장소: 여기_

* 공식문서: nestjs_

.. _박정태: https://github.com/pjt3591oo
.. _여기: https://github.com/pjt3591oo/nestjs_translate
.. _nestjs: https://docs.nestjs.com/

.. toctree::
    :maxdepth: 2
    :caption: INTRODUCTION
    :glob:
    :titlesonly:

    introduction/introduction.md

.. toctree::
    :maxdepth: 2
    :caption: OVERVIEW
    :glob:
    :titlesonly:

    overview/first_step.md
    overview/controllers.md
    overview/providers.md
    overview/modules.md
    overview/middleware.md
    overview/exception_filters.md
    overview/pipes.md
    overview/guards.md
    overview/interceptors.md
    overview/custom_decorators.md

.. toctree::
    :maxdepth: 2
    :caption: FUNDAMENTALS 
    :glob:
    :titlesonly:

    fundamentals/custom_providers.md
    fundamentals/asynchronous_providers.md
    fundamentals/dynamic_modules.md
    fundamentals/circular_dependency.md
    fundamentals/injection_scopes.md
    fundamentals/lifecycle_events.md
    fundamentals/platform_agnosticism.md
    fundamentals/testing.md

.. toctree::
    :maxdepth: 2
    :caption: TECHNIQUES 
    :glob:
    :titlesonly:

    techniques/authentication.md
    techniques/database.md
    techniques/mongo.md
    techniques/configuration.md
    techniques/validation.md
    techniques/caching.md
    techniques/serialization.md
    techniques/task_scheduling.md
    techniques/compression.md
    techniques/security.md
    techniques/queues.md
    techniques/logger.md
    techniques/file_upload.md
    techniques/http_module.md
    techniques/model-view-controller.md
    techniques/performance.md

.. toctree::
    :maxdepth: 2
    :caption: GRAPHQL 
    :glob:
    :titlesonly:
    
    graphql/quick_start.md
    graphql/resolvers.md
    graphql/mutations.md
    graphql/subscriptions.md
    graphql/scalars.md
    graphql/tooling.md

.. toctree::
    :maxdepth: 2
    :caption: WEBSOCKETS 
    :glob:
    :titlesonly:
    
    websockets/gateways.md
    websockets/exception_filters.md
    websockets/pipes.md
    websockets/guards.md
    websockets/interceptors.md
    websockets/adapters.md

.. toctree::
    :maxdepth: 2
    :caption: MICROSERVICES 
    :glob:
    :titlesonly:
    
    microservices/overview.md
    microservices/redis.md
    microservices/MQTT.md
    microservices/NATS.md
    microservices/RabbitMQ.md
    microservices/gRPC.md
    microservices/exception_filters.md
    microservices/pipes.md
    microservices/guards.md
    microservices/interceptors.md

.. toctree::
    :maxdepth: 2
    :caption: APPLICATION CONTEXT 
    :glob:
    :titlesonly:
    
    application_context.md

.. toctree::
    :maxdepth: 2
    :caption: CLI
    :glob:
    :titlesonly:
    
    cli/overview.md
    cli/workspaces.md
    cli/libraries.md
    cli/usage.md
    cli/scripts.md

.. toctree::
    :maxdepth: 2
    :caption: RECIPES
    :glob:
    :titlesonly:

    recipes/TypeORM.md
    recipes/mongoose.md
    recipes/sequelize.md
    recipes/CQRS.md
    recipes/OpenAPI.md
    recipes/prisma.md
    recipes/health_checks.md
    recipes/documentation.md
    recipes/CRUD_utilities.md
    recipes/hot_reload.md
    recipes/serve_static.md

.. toctree::
    :maxdepth: 2
    :caption: FAQ
    :glob:
    :titlesonly:

    faq/HTTP_adapter.md
    faq/Global_path_prefix.md
    faq/Hybrid_application.md
    faq/HTTPS_multiple_servers.md
    faq/examples.md


.. toctree::
    :maxdepth: 2
    :caption: Migration Guide
    :glob:
    :titlesonly:
    
    migration_guide.md