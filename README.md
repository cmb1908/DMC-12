# DMC-12
12th attempt at a Document Metamorphosis Capsule.

This time machine project stores simple JSON documents in a Postgres database.  DMC-12 stores historic versions of documents as well as generating and storing differences between versions.  By storing all copies of a document as well as the differences, searching through history is optimised.

For data that changes over time (e.g. a company directory), using DMC-12 is an alternative to storing daily snapshots.  DMC-12 will use significantly less storage than snapshots and is much more performant when looking for record changes.
