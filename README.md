# AI in Biology Workshop

## Live Demo — Comparing Cells From the Same Donor

Can we use a plot to see how average APOBEC3A expression differs within each donor?

The demo uses synthetic data from six donors. Each donor has two values for the same gene, APOBEC3A. One is the average expression in basal tumor cells with detectable HPV16 RNA. The other is the average in basal tumor cells where HPV16 RNA was not detected.

### Option 1: Make the plot in ChatGPT

1. Download [demo_data.csv](demo_data.csv).
2. Open a new ChatGPT conversation and upload the CSV.
3. Open [demo_prompt.txt](demo_prompt.txt), copy the prompt, and paste it into the chat.
4. Check that the plot has one line per donor, for a total of six lines.

### Option 2: Read and run the Python code in Google Colab

1. Download the same [demo_data.csv](demo_data.csv) and attach it in a new ChatGPT conversation.
2. Copy the [Colab prompt](demo_prompt_colab.txt) into the chat. Ask ChatGPT to return the Python code.
3. Open a new notebook at [Google Colab](https://colab.research.google.com/).
4. In Colab, open **Files** (folder icon) and upload `demo_data.csv`. Keep that filename.
5. Copy the generated Python code into a code cell. Read the comments, then click ▶ to run the cell.
6. Compare the table and plot with the direct ChatGPT result.

### Check one result by hand

For donor D01, the average expression is 2.0 in the HPV16 RNA undetected group and 1.2 in the detected group.

**Detected minus undetected = 1.2 − 2.0 = −0.8.**

The line for D01 should go down from left to right.

All values are made up for this teaching exercise.
