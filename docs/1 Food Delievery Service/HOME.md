# 1 Food Delievery Service

![diagram](https://www.plantuml.com/plantuml/svg/0/XLLDRnen4Br7od-OSgX0Ik7IKqyXX7nK8TcoH55FoEmEuDPhR_qHGgl-zuxjtMNvY9f3P7izxxrvCsCkZMNQkaASdttWCXCkHrXRMvelWu5cc_wAsxLRE8CwKzAYjFrC5GEMQyxagt2b6um-Vqe4a_PvyZ0GpAAnT3GVqMt69Uf-6S3Fpnw6tv-UP_EN-zdT_65yEtwyxlRyUOBQADdDdB6gG7q1dL6rxD1w26Nu3fkr0gLpsi1IgHoSuN85TerGg0KN2AmiwG9iS66unNwdrq1hqiIS9eq4E6qsa5gsN4OIuvTGOB50xL7CrbWiWDd0i0EWBPqLJB8LcafFe4f3m7pyPhibsnPar2rviM5RWa_Y0LGddf7kePPC01dxoZEad3IKMcLeGbuLnX7sJaayt4ze4dG5hlZPKqqgiQqaw8Op5vNy2s0o1_RAk61a9BVRGDhGNYadSwQttMLETpittlnh5FmLzHRIAB_JWp_dPq1_JTsxL8XXMLB42ow0Le9dp78bEq4pospWdMBkta8DX50R0tKR6B1LlMEvbHI46fJjqyJgHwP9x0JQUCGRuQoDNJIMR27m0BqKZ8olUgff9qx5BsWaohMIQ4uGif8JuXNBVYBf7oRtdk1HvTZ_OK9AuxUIl3R--8xsdfS9uVkpjW24Ml7i0kB0UUAOQR6hdmVAQvUj9ZQwTa9DlY2QQsRPWXdqb8aoTgKn_VRWTwbLkfMtRx4bMLGN7zQSFkXjx87CQOrLUm3DKB5BF_wVecZDQLFWn1jPJmDiwCK8kSzcILh7xqUsQtOYk1NJ7jre_6HlzgXYMhdL-bXdk7qyYd74ABwUi4QlhsJl8Fx4kALRcH6dvB-FKpu54Gf4_PxJkwLL0HzXeybRtu4-vElrrUXOV6rjJFcPz8QxwTFZuCZMbfd_kzu4pP-ZkDQZcr8tLmc1AtEsavWuimQfB5zMxKlTaqxQ6WZksAczLpUYxu5KwFUoVWdZYqMeV_thurCxB5zBxXH_EI9ewXZCzS67NTDqwHGpf75gYlPUGBivtukvf7J2pze_)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.