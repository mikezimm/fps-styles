npm version major/minor/patch
npm publish --access=public

npm install @mikezimm/fps-styles@1.0.9

Copy-Item "C:/Users/dev/Documents/GitHub/fps-styles/src"  -filter '*.css' "C:/Users/dev/Documents/GitHub/fps-styles/dist" -recurse -verbose

# Changelog

## @1.0.9 - 2022-Dec-20:
- updated easy-pages-spa and easy-pages-article to new maxwidth based on testing: https://github.com/mikezimm/fps-library-v2/issues/13

## @1.0.8 - 2022-Dec-19:
- changed blueBarLeft to blue-bar-left

## @1.0.7 - 2022-Dec-19:
- add leftMargin to blueBarLeft in reactListView.css

## @1.0.6 - 2022-Dec-19:
- add fps-list-header-bar to reactListView

## @1.0.5 - 2022-Dec-16:
- add reactListView.css from Drilldown

## @1.0.4 - 2022-Dec-16:
- Update easypages.css   'article' class:  width: calc(100% - 6em ) !important;

## @1.0.3 - 2022-Dec-16:
- Add PPCommandAccordion.css - From PropPaneCols Compnent
- Add PropPaneCols.css - From PropPaneCols Compnent

## @1.0.2 - 2022-Dec-14:
- add easy-pages-article to easypages.css
