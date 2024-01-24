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

| Sayfa                                                                 | Durum                 | Sebep       | Atanan             | Çeviren            | Gözden Geçiren                                             |
| --------------------------------------------------------------------- | --------------------- | ----------- | ------------------ | ------------------ | ---------------------------------------------------------- |
| [/index.md]({{url_for_pr(10444)}})                                    | :white_check_mark:    | Zaman Aşımı | [@hasansezertasan] | [@hasansezertasan] | [@alperiox], [@esrefzeki], [@bilalalpaslan], @mertssmnoglu |
| [/features.md]({{url_for_pr(10492)}})                                 | :nerd:                | Zaman Aşımı | [@bilalalpaslan]   |                    | [@hasansezertasan]                                         |
| [/fastapi-people.md]({{url_for_pr(10547)}})                           | :nerd:                | Zaman Aşımı | [@alperiox]        |                    |                                                            |
| [/python-types.md]({{url_for_pr(10445)}})                             | :nerd:                | Zaman Aşımı | [@esrefzeki]       |                    | [@hasansezertasan], [@bilalalpaslan]                       |
| [/alternatives.md]({{url_for_pr(10502)}})                             | :nerd:                | Yeni        | [@alperiox]        |                    | [@hasansezertasan]                                         |
| [/external-links.md]({{url_for_pr(10549)}})                           | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/benchmarks.md]({{url_for_pr(11005)}})                               | :white_check_mark:    | Zaman Aşımı | [@bilalalpaslan]   | [@hasansezertasan] |                                                            |
| [/newsletter.md]({{url_for_pr(10550)}})                               | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] | [@alperiox]                                                |
| `/project-generation.md`                                              | :construction:        | Yeni        | [@bilalalpaslan]   |                    |                                                            |
| `/async.md`                                                           | :construction:        | Yeni        | [@bilalalpaslan]   |                    |                                                            |
| `/contributing.md`                                                    | :construction:        | Yeni        | [@hasansezertasan] |                    |                                                            |
| `/help-fastapi.md`                                                    | :white_square_button: | Yeni        |                    |                    |                                                            |
| [/history-design-future.md]({{url_for_pr(11012)}})                    | :nerd:                | Yeni        | [@esrefzeki]       | [@hasansezertasan] |                                                            |
| `/release-notes.md`                                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| [/about/index.md]({{url_for_pr(11006)}})                              | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/help/index.md]({{url_for_pr(11013)}})                               | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| [/learn/index.md]({{url_for_pr(11014)}})                              | :white_check_mark:    | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/tutorial/index.md`                                                  | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/first-steps.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/path-params.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/query-params.md`                                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/body.md`                                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/query-params-str-validations.md`                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/path-params-numeric-validations.md`                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/body-multiple-params.md`                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/body-fields.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/body-nested-models.md`                                     | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/schema-extra-example.md`                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/extra-data-types.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/cookie-params.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/header-params.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/response-model.md`                                         | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/extra-models.md`                                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/response-status-code.md`                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/request-forms.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/request-files.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/request-forms-and-files.md`                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/handling-errors.md`                                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/path-operation-configuration.md`                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/encoder.md`                                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/body-updates.md`                                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/dependencies/index.md`                                     | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/dependencies/classes-as-dependencies.md`                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/dependencies/sub-dependencies.md`                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/dependencies/dependencies-in-path-operation-decorators.md` | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/dependencies/global-dependencies.md`                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/dependencies/dependencies-with-yield.md`                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/security/index.md`                                         | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/security/first-steps.md`                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/security/get-current-user.md`                              | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/security/simple-oauth2.md`                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/security/oauth2-jwt.md`                                    | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/middleware.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/cors.md`                                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/sql-databases.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/bigger-applications.md`                                    | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/background-tasks.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/metadata.md`                                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/static-files.md`                                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/testing.md`                                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/tutorial/debugging.md`                                              | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/index.md`                                                  | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/path-operation-advanced-configuration.md`                  | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/additional-status-codes.md`                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/response-directly.md`                                      | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/custom-response.md`                                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/additional-responses.md`                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/response-cookies.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/response-headers.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/response-change-status-code.md`                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/advanced-dependencies.md`                                  | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/security/index.md`                                         | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/security/oauth2-scopes.md`                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/security/http-basic-auth.md`                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/using-request-directly.md`                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/dataclasses.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/middleware.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/sub-applications.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/behind-a-proxy.md`                                         | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/templates.md`                                              | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/websockets.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/events.md`                                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/testing-websockets.md`                                     | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/testing-events.md`                                         | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/testing-dependencies.md`                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/testing-database.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/async-tests.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/settings.md`                                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/openapi-callbacks.md`                                      | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/openapi-webhooks.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/wsgi.md`                                                   | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/advanced/generate-clients.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/index.md`                                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/versions.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/https.md`                                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/manually.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/concepts.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/cloud.md`                                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/server-workers.md`                                       | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/deployment/docker.md`                                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| [/how-to/index.md]({{url_for_pr(11021)}})                             | :white_square_button: | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
| `/how-to/general.md`                                                  | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/sql-databases-peewee.md`                                     | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/async-sql-encode-databases.md`                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/nosql-databases-couchbase.md`                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/graphql.md`                                                  | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/custom-request-and-route.md`                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/conditional-openapi.md`                                      | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/extending-openapi.md`                                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/separate-openapi-schemas.md`                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/custom-docs-ui-assets.md`                                    | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/how-to/configure-swagger-ui.md`                                     | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/index.md`                                                 | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/fastapi.md`                                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/parameters.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/status.md`                                                | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/uploadfile.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/exceptions.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/dependencies.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/apirouter.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/background.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/request.md`                                               | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/websockets.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/httpconnection.md`                                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/response.md`                                              | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/responses.md`                                             | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/middleware.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/openapi/index.md`                                         | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/openapi/docs.md`                                          | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/openapi/models.md`                                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/security/index.md`                                        | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/encoders.md`                                              | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/staticfiles.md`                                           | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/templating.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| `/reference/testclient.md`                                            | :white_square_button: | Yeni        |                    |                    |                                                            |
| [/resources/index.md]({{url_for_pr(11020)}})                          | :white_square_button: | Yeni        | [@hasansezertasan] | [@hasansezertasan] |                                                            |
