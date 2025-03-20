### Checklist for the Pull Request Creator
- [ ] Add a comment/description with enough information for the reviewer to test easily. Link the ticket, information about config & the enviroment where the feature is enabled or how to change it.
- [ ] Ensure the code is testable.
- [ ] Add tests for both happy cases and reasonable edge cases.
- [ ] Ensure logs have been added if necessary.
- [ ] Ensure strings are localized and look correct.
- [ ] Remove any commented-out code or FIXME comments.
- [ ] If your ticket impacts backend data, ensure the data is correct on the backend.
- [ ] Document areas potentially impacted by this change for inclusion in manual tests.
- [ ] Test the feature and ensure it works as expected.
- [ ] (Optional) If this feature is toggleable, ensure the old flow works as it used to.

### Checklist for the Reviewer
- [ ] Test the feature and ensure it works as expected.
- [ ] (Optional) If this feature is toggleable, ensure the old flow works as it used to.
- [ ] Review the code for quality and readability.
- [ ] Ensure the code is adequately tested, covering both happy and reasonable edge cases.
