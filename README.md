In this README file, what each code files do and how to run the file is mentioned.

Empty Cells:
  Purpose: Count the empty cells in every column.
  How to run: ./empty_cells bgg_dataset.txt ';'

Preprocess:
  Purpose: Clean a semicolon-delimited raw dataset into a proper formatted TSV file by normalizing decimal points and line endings,
             converting separators to tabs and auto-filling missing IDs.
  How to run the file: ./preprocess <rawfile.txt>  > clean.tsv


analysis:
  Purpose: Answer the four research questions on a cleaned TSV. Read the TSV file (made using preprocess code) of board games and report the most popular
             game mechanics and domain, plus Pearson correlations between publication year/complexity and average rating.
  How to run the file: ./analysis <clean.tsv>
