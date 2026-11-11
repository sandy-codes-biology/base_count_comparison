# Base Count Comparison

Compares the A, T, C and G base counts of two DNA sequences from FASTA files and draws a side-by-side bar chart.

## What does it do?

1. Reads two FASTA files 📖
2. Counts the A, T, C and G bases in each sequence 🧮
3. Plots the counts as a grouped bar chart 📊

The example compares human insulin (NM_000207) and haemoglobin beta (NM_000518) mRNA sequences from NCBI!

## How to use it?

1. Install matplotlib: `pip install matplotlib`
2. Put your two FASTA files in the same folder as the notebook
3. In the first code cell, change the four settings lines to your own file names and labels
4. Run all cells

## Note

The chart shows raw counts, so a longer sequence will have taller bars simply because it has more bases.

*This was a beginner project made while learning Python and bioinformatics.*
