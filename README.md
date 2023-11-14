# Big-Data

## What is Big Data?
Big data are volumous and are often unstructured and come in huge variety of forms making storage in conventional relational databases very difficult or impossible. Multiple machines are required to store, analyse and process the data so distributed processing important.

## Volume, velocity and variety
- Volume - huge quanitities of data. (too big to fit into a single server)
- Velocity - Data are continuously being added to an already huge dataset so greater space capacity is needed. (streaming data, milliseco0nds to seconds to respond)
- Variety - There is a high range of data types so that data are unstructured. (data in many forms such as structured, unstructured, text, multimedia)

  ## Multiple servers
Because the quantity of data are so large, the data need to be processed in parallel (at the same time) over multiple machines. This means that programs have to be designed with concurrency in mind, that is they need to be thread-safe. This is where functional programming comes in.

## Machine learning
- Machine learning is a way of getting computers to make better predictions based on data.
- Look for patterns in data this can include anything from simple regression to neutral networks.
- Machine learning uses big data to find patterns that humans cannot see.

## Fact based model for representing data
- Facts are recorded with timestamps
- They are immutable, they cannot be deleted
- Data stores as atomic facts
- Immutable and always true using timestamps
- Each fact uniquely identifiable
- Raw - The rawer the data the better, because one can ask more questions.
- Immutable - Cannot change the data e.g a record of someone's address does not change.
- Perpetuity - Data will always be true. Although some one moved to a new address, it will always be true that that person lived at another address at a given time.

## Graph schema
Often there is a value in exploring relationships between connected entities in a dataset just like a relational database.
-Graph schemas are used to represent huge datasets of connected data when nodes (vertices) are the entities, and the edges are the relations between facts.
- Nodes can have properties.
- Nodes are not tied to a fixed schema --> flexibility.

![image](https://github.com/Minwauu/Big-Data/assets/110039102/3947a746-55f7-4be5-8cce-0e0d55cb782b)
