# Implicitome-Neo4j-Database

This database contains data from Implicitome.  There are 28535 subjects and objects, 202571584 relationships, and 405200238 properties.  The import takes approximately 10 minutes.

The database is located in /home/sachi/neo4j-community-2.2.3/data/implicitome.db.  Other relevant files are located in /home/sachi/implicitome.

### Database Structure

The nodes (vertices) of this database are composed of subjects, which are genes, and objects, which are things those genes affect.  The nodes have one property, which is the identifier used in the Implicitome dataset.

The relationships (edges) of this database connect genes to objects they affect.  The relationships are all of type RELATED_TO, and have a score and percentage indicating the calculated strength of the relationship between the subject and object.
