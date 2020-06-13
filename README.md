# TestCoverage

## Unit
Running 
```cmd
./gradlew clean test
```
generates unit test reports, and a coverage report (.exec), but not an HTML report

`app/build/reports/tests/testDebugUnitTest/index.html`

`app/build/jacoco/testDebugUnitTest.exec`

### Integration
Running
```cmd
./gradlew clean connectedCheck
```
generates integration test reports, and a coverage report (.ec), along with HTML report

`app/build/reports/androidTests/connected/index.html`

`app/build/outputs/code_coverage/debugAndroidTest/connected/[DEVICE NAME]-coverage.ec`

`app/build/reports/coverage/debug/index.html`

### Appium
TBD