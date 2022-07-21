The TechEvents application can be found on the Google Play Store and Apple App Store at the following URLs:
- https://apps.apple.com/us/app/apple-store/id1571982495
- https://play.google.com/store/apps/details?id=com.techevents&gl=RO

## TechEvents application testing suite

11 test cases covered the testing suite for the application on both iOS and Android distributions:
| #      | Test Case                                                                    |
|--------|------------------------------------------------------------------------------|
| TC-001 | [Application installation from Google Play Store](test-cases/TC-001.md)      |
| TC-002 | [Application main screen](test-cases/TC-002.md)                              |
| TC-003 | [Application events interaction](test-cases/TC-003.md)                       |
| TC-004 | [The application filter menu](test-cases/TC-004.md)                          |
| TC-005 | [The application main menu](test-cases/TC-005.md)                            |
| TC-006 | [The Add Event screen](test-cases/TC-006.md)                                 |
| TC-007 | [The Favorites event screen](test-cases/TC-007.md)                           |
| TC-008 | [The FAQ screen](test-cases/TC-008.md)                                       |
| TC-009 | [The Terms and Conditions screen](test-cases/TC-009.md)                      |
| TC-010 | [The Contact Screen](test-cases/TC-010.md)                                   |
| TC-011 | [Application installation from Apple App Store](test-cases/TC-011.md)        |

All the test cases were executed on all the available devices (iPhone 12 with iOS 15.5 and Samsung Galaxy S22 Ultra with Android 12), resulting in the following test executions with their results:

| Test Executions                                                              | Result  |
|------------------------------------------------------------------------------|---------|
| [TE-001](test-execution/TE-001.md)                                           | ✅ PASS |
| [TE-002](test-execution/TE-002.md)                                           | ✅ PASS |
| [TE-003](test-execution/TE-003.md)                                           | ⭕ FAIL |
| [TE-004](test-execution/TE-004.md)                                           | ✅ PASS |
| [TE-005](test-execution/TE-005.md)                                           | ⭕ FAIL |
| [TE-006](test-execution/TE-006.md)                                           | ⭕ FAIL |
| [TE-007](test-execution/TE-007.md)                                           | ✅ PASS |
| [TE-008](test-execution/TE-008.md)                                           | ✅ PASS |
| [TE-009](test-execution/TE-009.md)                                           | ✅ PASS |
| [TE-010](test-execution/TE-010.md)                                           | ✅ PASS |
| [TE-011](test-execution/TE-011.md)                                           | ✅ PASS |
| [TE-012](test-execution/TE-012.md)                                           | ✅ PASS |
| [TE-013](test-execution/TE-013.md)                                           | ✅ PASS |
| [TE-014](test-execution/TE-014.md)                                           | ✅ PASS |
| [TE-015](test-execution/TE-015.md)                                           | ⭕ FAIL |
| [TE-016](test-execution/TE-016.md)                                           | ⭕ FAIL |
| [TE-017](test-execution/TE-017.md)                                           | ✅ PASS |
| [TE-018](test-execution/TE-018.md)                                           | ✅ PASS |
| [TE-019](test-execution/TE-019.md)                                           | ✅ PASS |
| [TE-020](test-execution/TE-020.md)                                           | ✅ PASS |

5 of the 20 test executions failed, which means that 25% of the test executions were failing.

The failed test executions generated 11 bugs with low, medium, and high severity, some of them applicable on all the devices, and some specific to a device. The following bugs reports were created:

| #                                 |  Description                                                              | 
|-----------------------------------|---------------------------------------------------------------------------|
| [BUG-001](bug-reports/BUG-001.md) | Wrong End Date when adding an event to the calendar                       |
| [BUG-002](bug-reports/BUG-002.md) | After filtering from the main menu, the application doesn't display the filtered results |
| [BUG-003](bug-reports/BUG-003.md) | No Link Present on the powered by text |
| [BUG-004](bug-reports/BUG-004.md) | The user can input an invalid URL on the add event form |
| [BUG-005](bug-reports/BUG-005.md) | Various issues with the date field from the add event form |
| [BUG-006](bug-reports/BUG-006.md) | The user can input an invalid email on the add event form |
| [BUG-007](bug-reports/BUG-007.md) | Add event form is not submitted |
| [BUG-008](bug-reports/BUG-008.md) | Add event form inputs are misaligned |
| [BUG-009](bug-reports/BUG-009.md) | Add an event screen has a huge white space at the bottom of the screen |
| [BUG-010](bug-reports/BUG-010.md) | The add event form placeholders are not visible on iOS |
| [BUG-011](bug-reports/BUG-011.md) | The user can submit a virtually empty form |