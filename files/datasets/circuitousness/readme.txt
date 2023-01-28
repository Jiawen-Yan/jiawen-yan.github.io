********************************************
* TEXTUAL CIRCUITOUSNESS OF 10K FILES
* Date: Jan. 28, 2021
* Citation: Guest, Nicholas M. and Yan, Jiawen, The Fast and the Circuitous: Semantic Progression as a Type of Disclosure Complexity, Working Paper. Available at [SSRN](https://ssrn.com/abstract=4098951).
********************************************


To compute textual *CIRCUITOUS* of each document, we employ the following four step procedure: 1) pre-process document, 2) split document into chunks, 3) represent chunks in high-dimensional space, and 4) calculate progression complexity of circuitousness.

*CIRCUITOUS* reflects the order in which information is presented in a document. It is defined as the ratio between the total length of the path the document actually takes from chunk to chunk and the length of the shortest possible path. 

This dataset has two variables: 1) FILENAME, and 2) CIRCUIOUS. FILENAME records the filename in EDGAR system, and the CIRCUIOUS records the computed circuitousness. See Guest and Yan (2023) Appendix for more technical details on computing progression complexity. 