# multiomics
Measuring all the things

## What *is* multiomics?

- DNA-seq of an individual + RNA-seq
- RNA-Seq + ATAC-seq on similar populations (not necessarily identical cells). Are there relationships between accessible chromatin and RNA that influences gene expression?
- RNA-seq + imaging on similar populations
- RNA-seq + imaging on the SAME cells (via infrared imaging)

## Potential to-do's:
1) Ask DCP if their ingestion service can accommodate ingesting "planned" data: that is, an entry that consists of all metadata but lacking the actual data content, plus a date for when it will likely be available. That way, when everybody searches DCP for a particular data type, they see not just data that exists but also data that is coming in the future. This means a metadata field that contains either "Data exists" or "Estimated date data will exist". 
2) Each project that has its own place for data to exist (e.g. Brain Initiative) needs to contact HCA and decide how to interface with HCA's DCP so as to decide whether to duplicate the data or interface. 
3) Ask the HCA DCP to produce a best practices document for how they expect each project to interface with them. Should we submit our data to GEO, and DCP? And project websites? Just place it on our websites as a data dump? (no!)


## Benchmark datasets and interoperability

Ideally: Has both sequencing-based and imaging-based molecular measurements

- Brain Initiative is doing RNA-Seq + imaging + epigenomics on single cells from the brain region
- ENCODE is doing hematopoiesis and liver
- HCA also has its own
- Also bulk samples to help do QC for your single cells

### Need interoperability

- Every of these grants have a DCP
- Should be working at the "node level" to latch onto these existing initiatives to make sure all their data types are interoperable

### Fiducial markers

Ultimately, these different measurement modalities are in different manifolds and you need fiducial markers to align these datasets. We can start getting these fiducial markers through bulk data.

## Metadata

How do we come up with the metadata we need?
- Enforcing those standards
- e.g. DCC for neurons have already figured out what they need, how do we use their expertise?

## What has worked and what hasn't worked?

- Data registration - officially stating a mouse strain and timepoint to analyze
- Hematopoiesis: Bulk RNA-seq and ATAC-seq on sorted subpopulations to create the principal components


## Imaging specifics

- Need a place to put the data
- Need rich single cell data with morphology and transcriptomics from exactly the same cells
  - Some kind of fluorescent labels on the cells
  - Patch-Seq: Patch clamp the cell, get morphology, could measure electrical activity, then suck out the cytoplasmic material
- Need a place where we can click and download everything
