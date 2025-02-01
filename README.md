# MongoDB Aggregation Pipeline Bug

This repository demonstrates a common error in MongoDB aggregation pipelines that leads to unexpected results. The bug arises from an incorrect stage order within the pipeline, causing incorrect data aggregation.  The solution provides the correct pipeline to achieve the desired outcome.

## Bug
The provided aggregation pipeline is meant to group documents by a certain field, count occurrences, and then sort the results. Due to a flaw in the pipeline construction, the results are not correctly aggregated.

## Solution
The solution demonstrates the corrected aggregation pipeline, ensuring that data is correctly filtered, grouped, sorted, and counted.