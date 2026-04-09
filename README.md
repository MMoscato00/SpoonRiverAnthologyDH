# Spoon River Anthology Mention Dataset

This repository contains the structured dataset derived from Edgar Lee Masters' *Spoon River Anthology*, created to support the analysis and visualization of character mention interactions.

## Overview

The dataset represents the interpoetic network of the Anthology, including:

- **Edges**: character mentions between poems, with information about the type of mention and the edition.
- **Nodes**: poems, with unique identifiers and edition information.

This dataset allows scholars, students, and literature enthusiasts to explore narrative structures, character interactions, and network patterns within the Anthology.

## Contents

1. **Edges dataset**: `SpoonRiver_Mention_interactions_edges_attributes.xlsx`  
   Fields:
   - `Source`: the poem or character originating the mention  
   - `Target`: the poem or character being mentioned  
   - `Source_Mention_Type`: type of mention (direct, semi-direct, indirect)  
   - `Edition_Source`: edition of the Anthology where the mention occurs  

2. **Nodes dataset**: `SpoonRiver_Poems_nodes_attributes.xlsx`  
   Fields:
   - `Poems`: title of the poem  
   - `Id`: unique identifier of the poem  
   - `Edition`: edition of the Anthology  

## How to Use

The dataset is provided in Excel format for easy access and compatibility with most analysis tools.

## License

This dataset is released under **CC0 1.0 Universal (Public Domain)**. You are free to use, modify, and share it without restrictions, even for commercial purposes.

## Contact

For questions, suggestions, or collaborations, contact Mattia Moscato.
