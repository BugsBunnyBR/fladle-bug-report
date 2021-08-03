# fladle-bug-report
### Without quotes

```
./gradlew flankDoctor

> Task :app:flankDoctor FAILED
Warning: Version should be string gcloud -> device[Pixel2] -> version[28]

Total run duration: 0m  2s

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:flankDoctor'.
> Process 'command '/Users/julio.buenocotta/.sdkman/candidates/java/11.0.9.hs-adpt/bin/java'' finished with non-zero exit value 2

```


### With quotes

```
 ./gradlew flankDoctor                                                 

> Task :app:flankDoctor
Valid yml file

Total run duration: 0m  2s

Deprecated Gradle features were used in this build, making it incompatible with Gradle 8.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/7.0.2/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 4s
3 actionable tasks: 3 executed

```
