# README

### TODO:
  - Rails
    - Store `Reward#percentage` properly (TBD)
      - Or maybe store # points/miles back per 1$ spend?
    - Consider storing non-bonus rewards on Card as a Reward w/ a `nil` SpendCategory
    - Revisit efficiency of GraphQL index queries
  - GraphQL
    - Authorize mutations!
    - Reorganize queries/mutations into separate files
    - Investigate removing Rails entirely, moving to tool like Graphcool?
  - React/Redux:
    - Figure out Selectors
    - Apollo?
    - Add PropTypes to Container components
    - Normalize Action type naming convention
    - Set up ESLint and refactor accordingly
  - Webpack/general tooling
    - React CSS Modules plugin, to avoid camelCased CSS classes
    - Use `ExtractTextPlugin` to extract CSS into separate file
    - `autoprefixer`
