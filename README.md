# cassutil

General cassandra java-driver utilities and wrappers

## Driver wrapper

A class with various convenience methods that wraps the DSE java-driver, and works on the 
convenience structures that wrap statements in conjunction with timestamp, consistency, and other options

## Collating Result Sets

Result Sets that pull from two other result sets simultaneously, preserving order and resolving conflicts/merges

## Time Bucket mapping Result Sets

Result Sets that map to a set of tables representing time bucketed/sharded data.

## Time BUcket spanning Result Sets

Result Sets that span across time bucketed/sharded tables of data

## Autopaging Result Sets

Result Sets that wrap paging and logic to pull more results automatically. 