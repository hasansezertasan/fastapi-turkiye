# İlerleyiş

<!--
{% macro url_for_pr(number="0") -%}
    https://github.com/tiangolo/fastapi/pull/{{number}}
{%- endmacro %}
-->

## Emoji Haritası

| Emoji | Durum            | Açıklama                    |
| ----- | ---------------- | --------------------------- |
| 🤓     | İnceleme         | PR açıldı, Review ediliyor. |
| 🚧     | Yapım Aşamasında | Çalışma devam ediyor.       |
| 🔳     | Yapılacak        | Çevirmenini bekliyor.       |
| ✅     | Onaylandı        | Onaylandı.                  |

## İlerleyiş

| Sayfa                                                                     | Durum                 | Sebep       | Çeviren            | Gözden Geçiren                                             |
| ------------------------------------------------------------------------- | --------------------- | ----------- | ------------------ | ---------------------------------------------------------- |
| [docs/index.md]({{url_for_pr(10444)}})                                    | :nerd:                | Zaman Aşımı | [@hasansezertasan] | [@alperiox], [@esrefzeki], [@bilalalpaslan], @mertssmnoglu |
| [docs/features.md]({{url_for_pr(10492)}})                                 | :nerd:                | Zaman Aşımı | [@bilalalpaslan]   | [@hasansezertasan]                                         |
| [docs/fastapi-people.md]({{url_for_pr(10547)}})                           | :nerd:                | Zaman Aşımı | [@alperiox]        |                                                            |
| [docs/python-types.md]({{url_for_pr(10445)}})                             | :nerd:                | Zaman Aşımı | [@esrefzeki]       | [@hasansezertasan], [@bilalalpaslan]                       |
| [docs/alternatives.md]({{url_for_pr(10502)}})                             | :nerd:                | Yeni        | [@alperiox]        | [@hasansezertasan]                                         |
| [docs/external-links.md]({{url_for_pr(10549)}})                           | :nerd:                | Yeni        | [@hasansezertasan] |                                                            |
| `docs/benchmarks.md`                                                      | :construction:        | Zaman Aşımı | [@bilalalpaslan]   |                                                            |
| [docs/newsletter.md]({{url_for_pr(10550)}})                               | :nerd:                | Yeni        | [@hasansezertasan] | [@alperiox]                                                |
| `docs/project-generation.md`                                              | :construction:        | Yeni        | [@bilalalpaslan]   |                                                            |
| `docs/async.md`                                                           | :construction:        | Yeni        | [@bilalalpaslan]   |                                                            |
| `docs/contributing.md`                                                    | :construction:        | Yeni        | [@hasansezertasan] |                                                            |
| `docs/history-design-future.md`                                           | :construction:        | Yeni        | [@esrefzeki]       |                                                            |
| `docs/release-notes.md`                                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/help-fastapi.md`                                                    | :white_square_button: | Yeni        |                    |                                                            |
| `docs/about/index.md`                                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/help/index.md`                                                      | :white_square_button: | Yeni        |                    |                                                            |
| `docs/learn/index.md`                                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/index.md`                                                  | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/first-steps.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/path-params.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/query-params.md`                                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/body.md`                                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/query-params-str-validations.md`                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/path-params-numeric-validations.md`                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/body-multiple-params.md`                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/body-fields.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/body-nested-models.md`                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/schema-extra-example.md`                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/extra-data-types.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/cookie-params.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/header-params.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/response-model.md`                                         | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/extra-models.md`                                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/response-status-code.md`                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/request-forms.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/request-files.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/request-forms-and-files.md`                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/handling-errors.md`                                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/path-operation-configuration.md`                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/encoder.md`                                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/body-updates.md`                                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/dependencies/index.md`                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/dependencies/classes-as-dependencies.md`                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/dependencies/sub-dependencies.md`                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/dependencies/dependencies-in-path-operation-decorators.md` | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/dependencies/global-dependencies.md`                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/dependencies/dependencies-with-yield.md`                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/security/index.md`                                         | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/security/first-steps.md`                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/security/get-current-user.md`                              | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/security/simple-oauth2.md`                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/security/oauth2-jwt.md`                                    | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/middleware.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/cors.md`                                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/sql-databases.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/bigger-applications.md`                                    | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/background-tasks.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/metadata.md`                                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/static-files.md`                                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/testing.md`                                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/tutorial/debugging.md`                                              | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/index.md`                                                  | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/path-operation-advanced-configuration.md`                  | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/additional-status-codes.md`                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/response-directly.md`                                      | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/custom-response.md`                                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/additional-responses.md`                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/response-cookies.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/response-headers.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/response-change-status-code.md`                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/advanced-dependencies.md`                                  | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/security/index.md`                                         | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/security/oauth2-scopes.md`                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/security/http-basic-auth.md`                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/using-request-directly.md`                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/dataclasses.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/middleware.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/sub-applications.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/behind-a-proxy.md`                                         | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/templates.md`                                              | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/websockets.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/events.md`                                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/testing-websockets.md`                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/testing-events.md`                                         | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/testing-dependencies.md`                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/testing-database.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/async-tests.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/settings.md`                                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/openapi-callbacks.md`                                      | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/openapi-webhooks.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/wsgi.md`                                                   | :white_square_button: | Yeni        |                    |                                                            |
| `docs/advanced/generate-clients.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/index.md`                                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/versions.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/https.md`                                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/manually.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/concepts.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/cloud.md`                                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/server-workers.md`                                       | :white_square_button: | Yeni        |                    |                                                            |
| `docs/deployment/docker.md`                                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/index.md`                                                    | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/general.md`                                                  | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/sql-databases-peewee.md`                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/async-sql-encode-databases.md`                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/nosql-databases-couchbase.md`                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/graphql.md`                                                  | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/custom-request-and-route.md`                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/conditional-openapi.md`                                      | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/extending-openapi.md`                                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/separate-openapi-schemas.md`                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/custom-docs-ui-assets.md`                                    | :white_square_button: | Yeni        |                    |                                                            |
| `docs/how-to/configure-swagger-ui.md`                                     | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/index.md`                                                 | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/fastapi.md`                                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/parameters.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/status.md`                                                | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/uploadfile.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/exceptions.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/dependencies.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/apirouter.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/background.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/request.md`                                               | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/websockets.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/httpconnection.md`                                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/response.md`                                              | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/responses.md`                                             | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/middleware.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/openapi/index.md`                                         | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/openapi/docs.md`                                          | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/openapi/models.md`                                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/security/index.md`                                        | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/encoders.md`                                              | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/staticfiles.md`                                           | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/templating.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/reference/testclient.md`                                            | :white_square_button: | Yeni        |                    |                                                            |
| `docs/resources/index.md`                                                 | :white_square_button: | Yeni        |                    |                                                            |
