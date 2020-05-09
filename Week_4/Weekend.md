# Databases

## Entity Relationship Diagram: 

* Diagram that lays out how all the tables in a database are laid out. 

* Entity: A person place or thing you want to track in a database. They become tables.
  * Every occurence of an entity is an 'entity instance'.
  * Entity instances become a record or row of a table.

* Attributes: Describes various characteristics about an individual entity. They become columns in table.
  * Primary Key: an attribute or group of attributes that uniquely identifies an instance of the entity.

* Relationship: Describes how one or more entities interact with each other. Usually described w/ a verb.

* Cardinality: the count of instances that are allowed or are necessary between entity relationships.
  * Minimum cardinality describes the minimun number instances that are required in relationship
  * Maximum cardinality describes the maximum amount of instances allowd in the relationship.
  * One manditory: must have one and only one instance
  * Many manditory: must have one or more instances
  * One optional: do not need an instance but one allowed
  * Many optional: do not need an instance but but can have as many as needed.