# multiomics
Measuring all the things


## Potential to-do's:
1) Ask DCP if their ingestion service can accommodate ingesting "planned" data: that is, an entry that consists of all metadata but lacking the actual data content, plus a date for when it will likely be available. That way, when everybody searches DCP for a particular data type, they see not just data that exists but also data that is coming in the future. This means a metadata field that contains either "Data exists" or "Estimated date data will exist". 
2) Each project that has its own place for data to exist (e.g. Brain Initiative) needs to contact HCA and decide how to interface with HCA's DCP so as to decide whether to duplicate the data or interface. 


## Benchmark datasets and interoperability

Ideally: Has both sequencing-based and imaging-based molecular measurements

- Brain Initiative is doing RNA-Seq + imaging + epigenomics on single cells from the brain region
- ENCODE is doing hematopoiesis and liver
- HCA also has its own

### Need interoperability

- Every of these grants have a DCP
- Should be working at the "node level" to latch onto these existing initiatives to make sure all their data types are interoperable



## Metadata

How do we come up with the metadata we need?
- Enforcing those standards
- e.g. DCC for neurons have already figured out what they need, how do we use their expertise?
