This repository contains additional evaluation results for the master thesis "Automated Detection and Completion of Confluence for Graph Grammars".

The folders are structured in the following way:

Folder 'critical_pairs_before_completion':
- Information about the different used grammars and their critical pairs
- Each contained folder is a different grammar ("BT", "DLList", ...)
- For each grammar there are 3 PDFs
  - All critical pairs
  - The problematic critical pairs (not strongly joinable)
  - The rules of the initial grammar


Folder 'after_completion':
- Contains a folder for each different grammar
- The folder of each grammar contains folders for all different completion algorithms
- The names of the completion algorithm folders correspond to the diffeerent algorithms (A1-A11) from the thesis
  - A1: ruleRestriction
  - A2: completionAbstractionBlocking
  - A3: addRulesNewNonterminalHeuristic
  - A4: joinGeneratedNonterminals
  - A5: singleNonterminalRuleAddingHeuristic
  - A6: onlyRuleAdding
  - A7: onlyRuleAddingNotLocalConcretizable
  - A8: combinedAlgorithm1
  - A9: combinedAlgorithm1NoLocalConcretizabilityCheck
  - A10: combinedAlgorithm2
  - A11: combinedAlgorithm2NoLocalConcretizabilityCheck
- For every combination of grammar and completion algorithm there are 2 PDFs
  - The rules of the completed grammar
  - The final critical pairs (that are not strongly joinable)
  
File: 'overlapping_pruning.pdf':
- This PDF contains additional statistics for the pruned overlappings
