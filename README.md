# Truth space comparison

We propose new methods and algorithms of analytical truth space comparison for Relational Database queries.
Such a comparison aims to define the possibility of partial or full cache usage. The cache is stored on
user's computer and Database server is supposed to be remote. In case user query's result is contained in
cache we can simply take the data from there avoiding any server requests. The suggested method may also be
used for defining data missing in cache and performing query to only receive that data. Analytical
computations are also used to achieve this and it differs our approach from existing ones. Query comparison
algorithms are based on the Predicate Logic theory. Formulas are presented by logical constraints in SQL
and predicates correspond to SQL operations.
