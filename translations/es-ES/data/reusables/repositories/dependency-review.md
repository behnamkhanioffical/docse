{% ifversion fpt or ghes > 3.1 or ghae-issue-4864 or ghec %}
Adicionalmente,
{% data variables.product.prodname_dotcom %} puede revisar cualquier dependencia que se agregue, actualice o elimine en una solicitud de cambios que se haga contra la rama predeterminada de un repositorio así como marcar cualquier cambio que pudiera introducir una vulnerabilidad en tu proyecto. Esto te permite ubicar y tratar las dependencias vulnerables antes, en vez de después, de que lleguen a tu base de código. Para obtener más información, consulta la sección "[Revisar los cambios a las dependencias en una solicitud de cambios](/github/collaborating-with-issues-and-pull-requests/reviewing-dependency-changes-in-a-pull-request)".
{% endif %}
