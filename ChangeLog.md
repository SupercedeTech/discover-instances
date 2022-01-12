# Changelog for discover-instances

## Unreleased changes

## 0.2.0.0
- add discoverInstancesWithType, which also adds the generic Type
  to the discovered instance. This allows comparisons between types,
  for example to discover all ToJSON and FromJSON, now you can generate
  properties `fromJSON . toJSON = id`

## 0.1.0.0

- Initial Release
