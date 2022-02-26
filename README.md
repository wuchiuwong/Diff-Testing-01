# Diff-Testing-01
## TABLE 1: False negative bugs (about pattern implementation) in the examined static bug finders
Type | Bug pattern | Involved rules | issue url | status(fixed/confirmed/won't fix/await confirmation)
:-: | :-: | :-: | :-: | :-:
False negative about pattern implementation | P1. Fail in special data type | PMD: SingularField | [issue link](https://github.com/pmd/pmd/issues/2529) | await confirmation
False negative about pattern implementation | P1. Fail in special data type | SonarQube: String function use should be optimized for single characters | [issue link](https://community.sonarsource.com/t/false-negative-s3027-can-not-detect-single-unicode-character-like-u001b/26050) | won't fix
False negative about pattern implementation | P1. Fail in special data type | SonarQube: Objects should not be created only to getClass | [issue link](https://community.sonarsource.com/t/false-negative-s2133-can-not-detect-getclass-called-by-array-of-classes/26235) | fixed
False negative about pattern implementation | P1. Fail in special data type | PMD:RedundantFieldInitializer | [issue link](https://github.com/pmd/pmd/issues/2441) | fixed
False negative about pattern implementation | P1. Fail in special data type | SpotBugs: ICAST_BAD_SHIFT_AMOUNT | [issue link](https://github.com/spotbugs/spotbugs/issues/1143) | await confirmation
False negative about pattern implementation | P2. Fail in compound expression | ErrorProne: ToStringReturnsNull | [issue link](https://github.com/google/error-prone/issues/1659) | confirmed
False negative about pattern implementation | P2. Fail in compound expression | SpotBugs: QBA_QUESTIONABLE_BOOLEAN_ASSIGNMENT | [issue link](https://github.com/spotbugs/spotbugs/issues/1149) | won't fix
False negative about pattern implementation | P2. Fail in compound expression | SpotBugs: SA_LOCAL_SELF_ASSIGNMENT | [issue link](https://github.com/spotbugs/spotbugs/issues/1145) | won't fix
False negative about pattern implementation | P2. Fail in compound expression | SonarQube: Variables should not be self-assigned | [issue link](https://community.sonarsource.com/t/false-negative-s1656-can-not-detect-static-variables-self-assigned-in-a-special-case-foo-foo-bar/26317) | won't fix
False negative about pattern implementation | P2. Fail in compound expression | SonarQube: Fields should not be initialized to default values | [issue link](https://community.sonarsource.com/t/false-negative-s3052-can-not-detect-assignment-which-right-statement-has-a-type-conversion/26047) | fixed
False negative about pattern implementation | P3. Fail in implicit operation | ErrorProne: IntLongMath | [issue link](https://github.com/google/error-prone/issues/1663) | won't fix
False negative about pattern implementation | P3. Fail in implicit operation | SonarQube: Static fields should not be updated in constructors | [issue link](https://community.sonarsource.com/t/false-negative-s3010-can-not-detect-static-variables-updated-by/26049) | confirmed
False negative about pattern implementation | P3. Fail in implicit operation | SpotBugs: DMI_INVOKING_TOSTRING_ON_ARRAY | [issue link](https://github.com/spotbugs/spotbugs/issues/1147) | confirmed
False negative about pattern implementation | P3. Fail in implicit operation | ErrorProne: ArrayEquals | [issue link](https://github.com/google/error-prone/issues/1658) | await confirmation
False negative about pattern implementation | P4. Fail in multiple calling operations | PMD: UseCollectionIsEmpty | [issue link](https://github.com/pmd/pmd/issues/2543) | fixed
False negative about pattern implementation | P4. Fail in multiple calling operations | PMD: AvoidPrintStackTrace | [issue link](https://github.com/pmd/pmd/issues/2437) | fixed
False negative about pattern implementation | P4. Fail in multiple calling operations | PMD: ClassCastExceptionWithToArray | [issue link](https://github.com/pmd/pmd/issues/2535) | await confirmation
False negative about pattern implementation | P4. Fail in multiple calling operations | PMD: DontCallThreadRun | [issue link](https://github.com/pmd/pmd/issues/2538) | fixed
False negative about pattern implementation | P5. Fail in separated expressions | PMD: UseProperClassLoader | [issue link](https://github.com/pmd/pmd/issues/2544) | fixed
False negative about pattern implementation | P5. Fail in separated expressions | ErrorProne: ToStringReturnsNull | [issue link](https://github.com/google/error-prone/issues/1660) | confirmed
False negative about pattern implementation | P5. Fail in separated expressions | PMD: InstantiationToGetClass | [issue link](https://github.com/pmd/pmd/issues/2539) | await confirmation
False negative about pattern implementation | P6. Fail in unnecessary brackets | PMD: ReturnEmptyArrayRatherThanNull | [issue link](https://github.com/pmd/pmd/issues/2540) | await confirmation
False negative about pattern implementation | P6. Fail in unnecessary brackets | PMD: SimplifyConditional | [issue link](https://github.com/pmd/pmd/issues/2541) | await confirmation
False negative about pattern implementation | P6. Fail in unnecessary brackets | SonarQube: Switch statements should not contain non-case labels | [issue link](https://community.sonarsource.com/t/false-negative-s1219-can-not-detect-non-case-labels-which-are-wrapped-in-braces/26233) | fixed
False negative about pattern implementation | P7. Fail in variables | PMD: FinalFieldCouldBeStatic | [issue link](https://github.com/pmd/pmd/issues/2440) | await confirmation
False negative about pattern implementation | P7. Fail in variables | PMD: AvoidDecimalLiteralsInBigDecimalConstructor | [issue link](https://github.com/pmd/pmd/issues/2532) | fixed
False negative about pattern implementation | Others | PMD: AvoidThrowingNullPointerException | [issue link](https://github.com/pmd/pmd/issues/2533) | await confirmation
False negative about pattern implementation | Others | PMD: StringToString | [issue link](https://github.com/pmd/pmd/issues/2530) | fixed
False negative about pattern implementation | Others | PMD: SimplifyBooleanExpressions | [issue link](https://github.com/pmd/pmd/issues/2585) | await confirmation

## TABLE 2: False negative bugs (about rule definition) in the examined static bug finders.
Type | Bug pattern | Involved rules | issue url | status(fixed/confirmed/won't fix/await confirmation)
:-: | :-: | :-: | :-: | :-:
False negative bugs about rule definition | P8. Miss comparable method | PMD: UseLocaleWithCaseConversions | [issue link](https://github.com/pmd/pmd/issues/2584) | await confirmation
False negative bugs about rule definition | P8. Miss comparable method | ErrorProne: BoxedPrimitiveEquality | [issue link](https://github.com/google/error-prone/issues/1661) | won't fix
False negative bugs about rule definition | P8. Miss comparable method | SonarQube: Java.lang.Error should not be extended | [issue link](https://community.sonarsource.com/t/suggestion-let-rule-s1194-detect-more-specific-errors-is-recommended/26163) | fixed
False negative bugs about rule definition | P8. Miss comparable method | SonarQube: Execution of the Garbage Collector should be triggered only by the JVM | [issue link](https://community.sonarsource.com/t/suggestion-let-rule-s1215-detect-case-system-runfinalization-is-recommended/26162) | fixed
False negative bugs about rule definition | P9. Miss comparable data type or operation | SonarQube: Redundant modifiers should not be used | [issue link](https://community.sonarsource.com/t/suggestion-let-rule-s2333-detect-redundant-modifiers-of-interface-is-recommended/26232) | fixed
False negative bugs about rule definition | P9. Miss comparable data type or operation | PMD: AvoidArrayLoops | [issue link](https://github.com/pmd/pmd/issues/2587) | fixed
False negative bugs about rule definition | P9. Miss comparable data type or operation | SpotBugs: ICAST_INTEGER_MULTIPLY_CAST_TO_LONG | [issue link](https://github.com/spotbugs/spotbugs/issues/1146) | await confirmation
False negative bugs about rule definition | P10. Miss subclass or superclass | PMD: ReturnEmptyArrayRatherThanNull | [issue link](https://github.com/pmd/pmd/issues/2588) | await confirmation
False negative bugs about rule definition | P10. Miss subclass or superclass | PMD: AvoidCatchingThrowable | [issue link](https://github.com/pmd/pmd/issues/2583) | await confirmation

## TABLE 3: False positive bugs in the examined static bug finders
Type | Bug pattern | Involved rules | issue url | status(fixed/confirmed/won't fix/await confirmation)
:-: | :-: | :-: | :-: | :-:
False positive bugs in the examined static bug finders | P11. Poor handling of method with same name | PMD: UseNotifyAllInsteadOfNotify | [issue link](https://github.com/pmd/pmd/issues/2577) | fixed
False positive bugs in the examined static bug finders | P11. Poor handling of method with same name | SonarQube: Object.finalize() should remain protected (versus public) when overriding | [issue link](https://community.sonarsource.com/t/false-positive-s1174-detected-override-of-finalize-with-arguments/26364) | fixed
False positive bugs in the examined static bug finders | P12. Setting over-sized scope | PMD: AvoidThrowingNullPointerException | [issue link](https://github.com/pmd/pmd/issues/2580) | fixed
False positive bugs in the examined static bug finders | P12. Setting over-sized scope | SpotBugs: SF_SWITCH_NO_DEFAULT | [issue link](https://github.com/spotbugs/spotbugs/issues/1148) | await confirmation
False positive bugs in the examined static bug finders | P12. Setting over-sized scope | PMD: AvoidCallingFinalize | [issue link](https://github.com/pmd/pmd/issues/2578) | fixed
False positive bugs in the examined static bug finders | P13. Neglecting corner case | PMD: MissingBreakInSwitch | [issue link](https://github.com/pmd/pmd/issues/2579) | fixed
False positive bugs in the examined static bug finders | P13. Neglecting corner case | PMD: AvoidReassigningLoopVariables | [issue link](https://github.com/pmd/pmd/issues/2595) | won't fix