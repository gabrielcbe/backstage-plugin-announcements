# @procore-oss/backstage-plugin-search-backend-module-announcements

## 0.2.0

### Minor Changes

- e811647: upgrade to 1.25.0 and integrate new authentication system

### Patch Changes

- Updated dependencies [e811647]
  - @procore-oss/backstage-plugin-announcements-common@0.2.0
  - @procore-oss/backstage-plugin-announcements-node@0.2.0

## 0.1.1

### Patch Changes

- 2b03aeb: Consolidate duplicated types into the common package.
- e5c0685: Refactor the AnnouncementsCollatorFactory to use the service coming from the new `announcements-node` package. This removes the modules dependency on `announcements-backend` which we ultimately don't want.
- ee57cf2: Export collators from search backend module and deprecate the collators coming from `announcements-backend`. Users are recommended to update their imports to use `@procore-oss/backstage-plugin-search-backend-module-announcements`.
- Updated dependencies [2b03aeb]
  - @procore-oss/backstage-plugin-announcements-common@0.1.4
  - @procore-oss/backstage-plugin-announcements-node@0.1.1