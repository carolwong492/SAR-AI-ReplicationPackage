
# Replication Package for: An Exploratory Study on SAR Patterns Within Agentic AI Pull Requests
## December 11, 2025

This replication package accompanies "An Exploratory Study on SAR Patterns Within Agentic AI Pull Requests" by Carol Wong, Kye Steele, Loelle Lam, Benjamin Crawford. 
<!---
(forthcoming). "Article Title". Journal Title. DOI.
Include as much detail in the article citation as you can.
-->

# Description of programs/code

<!---
Give a high-level overview of the program files and their purpose. Remove redundant/ obsolete files from the Replication archive.
-->
The program files in this replication package contain the statistical tests used to explore the distribution of SAR patterns within Agentic AI pull requests, as well as their impacts on merge time and acceptance rates. The original dataset is available on [HuggingFace](https://huggingface.co/datasets/hao-li/AIDev). 

- Files in `Data Analysis/` consist of the SAR pattern lists that compose the RegEx pattern used in the statistical tests.
- Files in `Statistical Tests/` will run the tests associated with each research question. The research question files can be run in any sequence, though the code within should be run in order.

# Requirements
- Python 3.12
- Required packages:
  - pandas
  - numpy
  - sys
  - os

# Running the Analyses

- Clone or download the repository.
- Create the Python 3.12 environment and install dependencies.
- Run the scripts in Statistical Tests/.
- Each research-question script can be executed independently.
- Code blocks inside each script must be run in order.
  
### License for Code

The code is licensed under a MIT license. See [LICENSE](LICENSE) for details.

