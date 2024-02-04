---
hide:
  - navigation
---
# İlerleyiş

<!--
{% macro url_for_pr(number="0") -%}
    https://github.com/tiangolo/fastapi/pull/{{number}}
{%- endmacro %}
{% macro pr_ref(number="0") -%}
    [{{number}}](https://github.com/tiangolo/fastapi/pull/{{number}})
{%- endmacro %}
{% macro file_ref(path) -%}
    [{{path}}](https://github.com/tiangolo/fastapi/blob/master/docs/en/docs{{path}})
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

| Sayfa                                       | Bağlantı          | Durum                 | Sebep       | Gönüllü            | Çeviren            | Gözden Geçiren                                             |
| ------------------------------------------- | ----------------- | --------------------- | ----------- | ------------------ | ------------------ | ---------------------------------------------------------- |
| `/index.md`                                 | {{pr_ref(10444)}} | :white_check_mark:    | Zaman Aşımı | [@hasansezertasan] | [@hasansezertasan] | [@alperiox], [@esrefzeki], [@bilalalpaslan], @mertssmnoglu |
| `/python-types.md`                          | {{pr_ref(10445)}} | :nerd:                | Zaman Aşımı | [@esrefzeki]       | [@esrefzeki]       | [@hasansezertasan], [@bilalalpaslan]                       |
| `/features.md`                              | {{pr_ref(10492)}} | :nerd:                | Zaman Aşımı | [@bilalalpaslan]   | [@bilalalpaslan]   | [@hasansezertasan]                                         |
| `/alternatives.md`                          | {{pr_ref(10502)}} | :white_check_mark:    | Yeni        | [@alperiox]        | [@alperiox]        | [@hasansezertasan]                                         |
| `/fastapi-people.md`                        | {{pr_ref(10547)}} | :nerd:                | Zaman Aşımı | [@alperiox]        | [@alperiox]        | [@hasansezertasan]                                         |
| `/external-links.md`                        | {{pr_ref(10549)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/newsletter.md`                            | {{pr_ref(10550)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] | [@alperiox]                                                |
| `/benchmarks.md`                            | {{pr_ref(11005)}} | :white_check_mark:    | Zaman Aşımı | [@bilalalpaslan]   | [@hasansezertasan] |                                                            |
| `/about/index.md`                           | {{pr_ref(11006)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/history-design-future.md`                 | {{pr_ref(11012)}} | :white_check_mark:    | Yeni        | [@esrefzeki]       | [@hasansezertasan] |                                                            |
| `/help/index.md`                            | {{pr_ref(11013)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/learn/index.md`                           | {{pr_ref(11014)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/resources/index.md`                       | {{pr_ref(11020)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/how-to/index.md`                          | {{pr_ref(11021)}} | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/tutorial/path-params.md`                  | {{pr_ref(11073)}} | :nerd:                | Yeni        | [@emrhnsyts]       | [@emrhnsyts]       | [@hasansezertasan]                                         |
| `/tutorial/query-params.md`                 | {{pr_ref(11078)}} | :nerd:                | Yeni        | [@emrhnsyts]       | [@emrhnsyts]       |                                                            |
| `/tutorial/body.md`                         | {{pr_ref(11087)}} | :nerd:                | Yeni        | [@emrhnsyts]       | [@emrhnsyts]       |                                                            |
| `/tutorial/query-params-str-validations.md` |                   | :construction:        | Yeni        | [@emrhnsyts]       | [@emrhnsyts]       |                                                            |
| `/project-generation.md`                    |                   | :construction:        | Yeni        | [@bilalalpaslan]   |                    |                                                            |
| `/async.md`                                 |                   | :construction:        | Yeni        | [@bilalalpaslan]   |                    |                                                            |
| `/help-fastapi.md`                          |                   | :white_square_button: | Yeni        | [@hasansezertasan] |                    |                                                            |
| `/contributing.md`                          |                   | :white_square_button: | Yeni        | [@hasansezertasan] |                    |                                                            |
| `/tutorial/first-steps.md`                  |                   | :white_square_button: | Yeni        | [@hasansezertasan] |                    |                                                            |
| `/advanced/index.md`                        |                   | :white_square_button: | Yeni        | [@alperiox]        |                    |                                                            |
| `/deployment/index.md`                      |                   | :white_square_button: | Yeni        | [@alperiox]        |                    |                                                            |
| `/tutorial/index.md`                        |                   | :white_square_button: | Yeni        | [@alperiox]        |                    |                                                            |

## Durum

<!-- Bu takip için data approach uygulanacak ve her gün çalışacak durum takip sistemi yazılacak. -->

| Sayfa                                                                               | Durum       |
| ----------------------------------------------------------------------------------- | ----------- |
| {{file_ref("/index.md")}}                                                           | Zaman Aşımı |
| {{file_ref("/features.md")}}                                                        | Zaman Aşımı |
| {{file_ref("/learn/index.md")}}                                                     | Güncel      |
| {{file_ref("/python-types.md")}}                                                    | Zaman Aşımı |
| {{file_ref("/async.md")}}                                                           | Zaman Aşımı |
| {{file_ref("/tutorial/index.md")}}                                                  | Çevirilmedi |
| {{file_ref("/tutorial/first-steps.md")}}                                            | Zaman Aşımı |
| {{file_ref("/tutorial/path-params.md")}}                                            | Çevirilmedi |
| {{file_ref("/tutorial/query-params.md")}}                                           | Çevirilmedi |
| {{file_ref("/tutorial/body.md")}}                                                   | Çevirilmedi |
| {{file_ref("/tutorial/query-params-str-validations.md")}}                           | Çevirilmedi |
| {{file_ref("/tutorial/path-params-numeric-validations.md")}}                        | Çevirilmedi |
| {{file_ref("/tutorial/body-multiple-params.md")}}                                   | Çevirilmedi |
| {{file_ref("/tutorial/body-fields.md")}}                                            | Çevirilmedi |
| {{file_ref("/tutorial/body-nsted-models.md")}}                                      | Çevirilmedi |
| {{file_ref("/tutorial/schema-extra-example.md")}}                                   | Çevirilmedi |
| {{file_ref("/tutorial/extra-data-types.md")}}                                       | Çevirilmedi |
| {{file_ref("/tutorial/cookie-params.md")}}                                          | Çevirilmedi |
| {{file_ref("/tutorial/header-params.md")}}                                          | Çevirilmedi |
| {{file_ref("/tutorial/response-model.md")}}                                         | Çevirilmedi |
| {{file_ref("/tutorial/extra-models.md")}}                                           | Çevirilmedi |
| {{file_ref("/tutorial/response-status-code.md")}}                                   | Çevirilmedi |
| {{file_ref("/tutorial/request-forms.md")}}                                          | Çevirilmedi |
| {{file_ref("/tutorial/request-files.md")}}                                          | Çevirilmedi |
| {{file_ref("/tutorial/request-forms-and-files.md")}}                                | Çevirilmedi |
| {{file_ref("/tutorial/handling-errors.md")}}                                        | Çevirilmedi |
| {{file_ref("/tutorial/path-operation-configuration.md")}}                           | Çevirilmedi |
| {{file_ref("/tutorial/encoder.md")}}                                                | Çevirilmedi |
| {{file_ref("/tutorial/body-updates.md")}}                                           | Çevirilmedi |
| {{file_ref("/tutorial/dependencies/index.md")}}                                     | Çevirilmedi |
| {{file_ref("/tutorial/dependencies/classes-as-dependencies.md")}}                   | Çevirilmedi |
| {{file_ref("/tutorial/dependencies/sub-dependencies.md")}}                          | Çevirilmedi |
| {{file_ref("/tutorial/dependencies/dependencies-in-path-operation-decorators.md")}} | Çevirilmedi |
| {{file_ref("/tutorial/dependencies/global-dependencies.md")}}                       | Çevirilmedi |
| {{file_ref("/tutorial/dependencies/dependencies-with-yield.md")}}                   | Çevirilmedi |
| {{file_ref("/tutorial/security/index.md")}}                                         | Çevirilmedi |
| {{file_ref("/tutorial/security/first-steps.md")}}                                   | Çevirilmedi |
| {{file_ref("/tutorial/security/get-current-user.md")}}                              | Çevirilmedi |
| {{file_ref("/tutorial/security/simple-oauth2.md")}}                                 | Çevirilmedi |
| {{file_ref("/tutorial/security/oauth2-jwt.md")}}                                    | Çevirilmedi |
| {{file_ref("/tutorial/middleware.md")}}                                             | Çevirilmedi |
| {{file_ref("/tutorial/cors.md")}}                                                   | Çevirilmedi |
| {{file_ref("/tutorial/sql-database.md")}}                                           | Çevirilmedi |
| {{file_ref("/tutorial/bigger-applications.md")}}                                    | Çevirilmedi |
| {{file_ref("/tutorial/background-tasks.md")}}                                       | Çevirilmedi |
| {{file_ref("/tutorial/metadata.md")}}                                               | Çevirilmedi |
| {{file_ref("/tutorial/static-files.md")}}                                           | Çevirilmedi |
| {{file_ref("/tutorial/testing.md")}}                                                | Çevirilmedi |
| {{file_ref("/tutorial/debugging.md")}}                                              | Çevirilmedi |
| {{file_ref("/advanced/index.md")}}                                                  | Çevirilmedi |
| {{file_ref("/advanced/path-operation-advanced-configuration.md")}}                  | Çevirilmedi |
| {{file_ref("/advanced/additional-status-codes.md")}}                                | Çevirilmedi |
| {{file_ref("/advanced/response-directly.md")}}                                      | Çevirilmedi |
| {{file_ref("/advanced/custom-response.md")}}                                        | Çevirilmedi |
| {{file_ref("/advanced/additional-responses.md")}}                                   | Çevirilmedi |
| {{file_ref("/advanced/response-cookie.md")}}                                        | Çevirilmedi |
| {{file_ref("/advanced/response-headers.md")}}                                       | Çevirilmedi |
| {{file_ref("/advanced/response-change-status-code.md")}}                            | Çevirilmedi |
| {{file_ref("/advanced/advanced-dependencies.md")}}                                  | Çevirilmedi |
| {{file_ref("/advanced/security/index.md")}}                                         | Çevirilmedi |
| {{file_ref("/advanced/security/oauth2-scopes.md")}}                                 | Çevirilmedi |
| {{file_ref("/advanced/security/http-basic-auth.md")}}                               | Çevirilmedi |
| {{file_ref("/advanced/using-request-directly.md")}}                                 | Çevirilmedi |
| {{file_ref("/advanced/dataclasses.md")}}                                            | Çevirilmedi |
| {{file_ref("/advanced/middleware.md")}}                                             | Çevirilmedi |
| {{file_ref("/advanced/sub-applications.md")}}                                       | Çevirilmedi |
| {{file_ref("/advanced/behind-a-proxy.md")}}                                         | Çevirilmedi |
| {{file_ref("/advanced/templates.md")}}                                              | Çevirilmedi |
| {{file_ref("/advanced/websockets.md")}}                                             | Çevirilmedi |
| {{file_ref("/advanced/events.md")}}                                                 | Çevirilmedi |
| {{file_ref("/advanced/testing-websockets.md")}}                                     | Çevirilmedi |
| {{file_ref("/advanced/testing-events.md")}}                                         | Çevirilmedi |
| {{file_ref("/advanced/testing-dependencies.md")}}                                   | Çevirilmedi |
| {{file_ref("/advanced/testing-database.md")}}                                       | Çevirilmedi |
| {{file_ref("/advanced/async-tests.md")}}                                            | Çevirilmedi |
| {{file_ref("/advanced/settings.md")}}                                               | Çevirilmedi |
| {{file_ref("/advanced/openapi-callbacks.md")}}                                      | Çevirilmedi |
| {{file_ref("/advanced/openapi-webhooks.md")}}                                       | Çevirilmedi |
| {{file_ref("/advanced/wsgi.md")}}                                                   | Çevirilmedi |
| {{file_ref("/advanced/generate-clients.md")}}                                       | Çevirilmedi |
| {{file_ref("/deployment/index.md")}}                                                | Çevirilmedi |
| {{file_ref("/deployment/versions.md")}}                                             | Çevirilmedi |
| {{file_ref("/deployment/https.md")}}                                                | Çevirilmedi |
| {{file_ref("/deployment/manually.md")}}                                             | Çevirilmedi |
| {{file_ref("/deployment/concepts.md")}}                                             | Çevirilmedi |
| {{file_ref("/deployment/cloud.md")}}                                                | Çevirilmedi |
| {{file_ref("/deployment/server-workers.md")}}                                       | Çevirilmedi |
| {{file_ref("/deployment/docker.md")}}                                               | Çevirilmedi |
| {{file_ref("/how-to/index.md")}}                                                    | Çevirilmedi |
| {{file_ref("/how-to/general.md")}}                                                  | Çevirilmedi |
| {{file_ref("/how-to/graphql.md")}}                                                  | Çevirilmedi |
| {{file_ref("/how-to/custom-request-and-route.md")}}                                 | Çevirilmedi |
| {{file_ref("/how-to/conditional-openapi.md")}}                                      | Çevirilmedi |
| {{file_ref("/how-to/extending-openapi.md")}}                                        | Çevirilmedi |
| {{file_ref("/how-to/separate-openapi-schemas.md")}}                                 | Çevirilmedi |
| {{file_ref("/how-to/custom-docs-ui-assets.md")}}                                    | Çevirilmedi |
| {{file_ref("/how-to/configure-swagger-ui.md")}}                                     | Çevirilmedi |
| {{file_ref("/how-to/sql-databases-peewee.md")}}                                     | Çevirilmedi |
| {{file_ref("/how-to/async-sql-encode-databases.md")}}                               | Çevirilmedi |
| {{file_ref("/how-to/nosql-databases-couchbase.md")}}                                | Çevirilmedi |
| {{file_ref("/reference/index.md")}}                                                 | Çevirilmedi |
| {{file_ref("/reference/fastapi.md")}}                                               | Çevirilmedi |
| {{file_ref("/reference/parameters.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/status.md")}}                                                | Çevirilmedi |
| {{file_ref("/reference/uploadfile.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/exceptions.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/dependencies.md")}}                                          | Çevirilmedi |
| {{file_ref("/reference/apirouter.md")}}                                             | Çevirilmedi |
| {{file_ref("/reference/background.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/request.md")}}                                               | Çevirilmedi |
| {{file_ref("/reference/websockets.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/httpconnection.md")}}                                        | Çevirilmedi |
| {{file_ref("/reference/response.md")}}                                              | Çevirilmedi |
| {{file_ref("/reference/responses.md")}}                                             | Çevirilmedi |
| {{file_ref("/reference/middleware.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/openapi/index.md")}}                                         | Çevirilmedi |
| {{file_ref("/reference/openapi/docs.md")}}                                          | Çevirilmedi |
| {{file_ref("/reference/openapi/models.md")}}                                        | Çevirilmedi |
| {{file_ref("/reference/security/index.md")}}                                        | Çevirilmedi |
| {{file_ref("/reference/encoders.md")}}                                              | Çevirilmedi |
| {{file_ref("/reference/staticfiles.md")}}                                           | Çevirilmedi |
| {{file_ref("/reference/templating.md")}}                                            | Çevirilmedi |
| {{file_ref("/reference/testclient.md")}}                                            | Çevirilmedi |
| {{file_ref("/fastapi-people.md")}}                                                  | Çevirilmedi |
| {{file_ref("/resources/index.md")}}                                                 | Çevirilmedi |
| {{file_ref("/project-generation.md")}}                                              | Çevirilmedi |
| {{file_ref("/external-links.md")}}                                                  | Çevirilmedi |
| {{file_ref("/newsletter.md")}}                                                      | Çevirilmedi |
| {{file_ref("/about/index.md")}}                                                     | Çevirilmedi |
| {{file_ref("/alternatives.md")}}                                                    | Güncel      |
| {{file_ref("/history-design-future.md")}}                                           | Güncel      |
| {{file_ref("/benchmarks.md")}}                                                      | Güncel      |
| {{file_ref("/help/index.md")}}                                                      | Güncel      |
| {{file_ref("/help-fastapi.md")}}                                                    | Çevirilmedi |
| {{file_ref("/contributing.md")}}                                                    | Çevirilmedi |
| {{file_ref("/release-notes.md")}}                                                   | Çevirilmedi |
