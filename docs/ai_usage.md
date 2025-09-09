

 📝 AI Assistance Report

A brief record of where I used AI tools during Beginning Bioinformatics (Part 3). All final implementations were typed, executed, and validated by me. AI was used only for guidance and not as a substitute for running or verifying the solutions.


 Log 1 — Repository + Colab Setup

AI tool/model: ChatGPT (GPT5)
What I needed help with: Stepbystep instructions for making a GitHub repository, adding the correct folders (`docs/`, `notebooks/`), committing my Colab notebook to `notebooks/Bioinformatics_Module03.ipynb`, and creating a submission tag.
Prompt style: “Explain how to prepare my repo structure so the submission matches exactly what the rubric asks.”
Adjustments I made: I created my own commit messages, filled in the `README.md` with my name/UTA ID/section, and checked that the repo was set to public.
Verification: I opened the repo in GitHub to confirm that the notebook appeared under `/notebooks/`, the docs file rendered, and the tag link ended with `/tree/week3submission`.



 Log 2 — Early Practice (P6–P8)

AI tool/model: ChatGPT (GPT5)
What I needed help with: Short Python demos for input, list operations, and string/list slicing.
Prompt style: “Provide tiny examples for Colab cells on input(), list editing, and slices.”
Adjustments I made: I renamed variables to be more meaningful, inserted comments on how indexing works, and added sample printouts.
Verification: I executed the code directly in Colab and checked that the outputs matched my expectations (e.g., slices produced exactly the target substrings).



 Log 3 — DNA → RNA (Rosalind)

AI tool/model: ChatGPT (GPT5) with Biopython `Seq`
What I needed help with: A reliable transcription routine that would handle messy inputs and convert T→U.
Prompt style: “How do I clean stray text and safely transcribe DNA into RNA?”
Adjustments I made: I rewrote the cleaning function to only keep `A/C/G/T` characters, and I added a plain `.replace()` method for redundancy.
Verification: I compared DNA and RNA lengths to ensure no bases were dropped, and I visually checked the first/last regions of the sequence.

 Log 4 — File Handling (P13–P15)

AI tool/model: ChatGPT (GPT5)
What I needed help with: Clear examples of reading files using `read()`, `readline()`, and `readlines()`, plus avoiding duplicate blank lines when printing.
Prompt style: “Show me standard filereading snippets with comments.”
Adjustments I made: I switched to `print(line.rstrip())` and used `enumerate` to track line numbers.
Verification: I tested on a simple text file, confirmed the even lines printed, and no extra whitespace appeared.


 Log 5 — Dictionaries + Word Counts

AI tool/model: ChatGPT (GPT5)
What I needed help with: Multiple ways to count word frequency, including dictionary logic and `Counter`.
Prompt style: “Show me different ways to count words, including one using `.count()` only once per word.”
Adjustments I made: I decided to keep the dictionary version and sorted the output for consistent ordering.
Verification: Tested with a small line like `red red blue red` and confirmed the counts matched expectations.



 Log 6 — FASTA Parsing & GC Content

AI tool/model: ChatGPT (GPT5) with Biopython `SeqIO` and `SeqUtils`
What I needed help with: A clean script to parse a FASTA file, compute GC percentages, and find the sequence with the highest GC%.
Prompt style: “Make a minimal Biopython example that reports GC% and the sequence ID with the max value.”
Adjustments I made: I rounded values to 6 decimals (to match Rosalind output style) and added a quick emptysequence guard.
Verification: Ran it on a practice FASTA file, manually recalculated GC on one sequence, and confirmed the correct ID was selected.



 Final Note

AI was primarily a support tool to help me structure code, remember library functions, and set up the repository. I wrote, ran, and debugged all final solutions myself. Every output was checked against small examples or actual input files before committing.

