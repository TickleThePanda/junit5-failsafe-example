The following is an example of a the failing integration tests caused by
the [`OutOfMemory`](https://github.com/junit-team/junit5/issues/809) and
fix.

This contains two Maven projects, the first without the fix, the second
with the fix:
 - `junit-failsafe-example-faily` - an example without the fix in the `pom.xml`
 - `junit-failsafe-example` - an example with the fix in the `pom`

To see the example of the integration tests successfully running in the second example use:
  - `mvn clean failsafe:integration-test`
