scala_library(
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'scrooge-serializer',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/org/apache/thrift:libthrift-0.5.0',
    'scrooge/scrooge-core',
    'util/util-app',
    'util/util-codec',
  ],
  strict_deps=True,
  exports=[
    'scrooge/scrooge-core',
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala'),
)
