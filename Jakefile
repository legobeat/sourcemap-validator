testTask('sourcemap-validator', function () {
  this.testFiles.include('tests/*');
  this.testFiles.exclude('tests/fixtures');
});

npmPublishTask('sourcemap-validator', function () {
  this.packageFiles.include([
    'index.js'
  , 'package.json'
  , 'Jakefile'
    ]);
  this.packageFiles.exclude([
  ]);
});
