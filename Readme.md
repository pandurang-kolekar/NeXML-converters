---
date: 2015-02-23
title: NeXML Converters
author: Pandurang Kolekar
Email: pandurang.kolekar@gmail.com
permalink: /NeXML-converters/
tags:
  - Readme
---

# NeXML Converters
These scripts were contributed during Tree-for-All Hackathon as the part of Phylogeny visulaization style sheets projects
https://github.com/OpenTreeOfLife/hackathon

Dependencies: Need Perl and its Bio::Phylo package to be installed on your computer

* Newick to NexML conversion

Use Newick-to-Nexml.pl program with following command
```perl
perl Newick-to-Nexml.pl <input_newick_file>
```
Example
```perl
perl Newick-to-Nexml.pl test.nwk
```
* Nexus to NexML conversion

Use Newick-to-Nexml.pl program with following command
```perl
perl Nexus-to-Nexml.pl <input_nexus_file>
```
Example
```perl
perl Nexus-to-Nexml.pl test.nexus
```
