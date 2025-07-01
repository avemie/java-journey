# Java Journey – Day 1
## Day 1 – środowisko gotowe
mvn -B archetype:generate \
  -DgroupId=com.avemie \
  -DartifactId=kanban-cli \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DarchetypeVersion=1.4 \
  -Dpackage=com.avemie.kanban
