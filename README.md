# How to Get a Job as a Bioinformatician as a Programmer

I worked as a professional programmer for 7 years (mostly Java) before starting as a bioinformatician in 2011. Here’s a guide with key aspects to consider.

---

## 1. Job Market

- **Limited Opportunities:**  
  Bioinformatics jobs are far fewer than general programming jobs. You’ll likely need to work harder, learn more, and may face lower pay and job security.
  
- **Upsides:**  
  You get more interesting work, greater freedom, and potentially higher job satisfaction.

---

## 2. Learning Resources

### Project Rosalind
- **What Is It?**  
  Think of it as “LeetCode for bioinformatics.” Check out the Bioinformatics Stronghold section at [Project Rosalind](https://rosalind.info/problems/list-view/).
- **Why Use It?**  
  It’s a fun way to learn biology basics and improve your skills. The challenges start easy and ramp up in difficulty. If you don’t find it engaging, bioinformatics might not be for you.

### Basic Biology
- **Learning the Fundamentals:**  
  Biology may seem full of memorization, but its core concepts—cells, genetics, DNA, RNA, and proteins—are accessible.
- **Resources:**  
  - WEHI animations: [WEHI Animations](https://www.wehi.edu.au/tv-content-type/animations/)
  - Start with a second-hand first-year textbook on biology (covering cells and intro genetics) and then skim a more advanced genetics book.
- **Key Terms:**  
  Familiarize yourself with nucleus, chromatin, transcription factors, DNA polymerase, exons, splicing, mRNA, transcription, ribosomes, and protein complexes.

---

## 3. Bio vs. Informatics Trade-Offs

There are three primary entry points:
1. **Train as a Bioinformatician:** (Masters, PhD)
2. **Train as a Biologist and Learn to Code:** (Masters, PhD in biology, then develop coding skills)
3. **Programmer with Self-Education in Biology:** (Bachelor’s plus self-study)

Think of it like role-playing stats:
- **PhD biologist + 6 months self-taught programming:** BIO: 8, PRO: 1  
- **Masters bioinformatician:** BIO: 4, PRO: 4  
- **Professional programmer:** BIO: 0, PRO: 8  
- **Programmer with 2 months self-education:** BIO: 1, PRO: 8

---

## 4. Types of Bioinformatics Jobs

The term “bioinformatician” covers roles with varying minimum skills in biology (BIO) and programming (PRO):

- **Individual Analyses for a Lab:**  
  A lab might perform a standard DNA sequencing assay (variant calling, RNAseq, ChiPseq) and then use mapping, QC, and analysis to produce spreadsheets/graphs.  
  *Minimum: BIO: 3, PRO: 1*

- **Building Automated Pipelines:**  
  Example: A genomics facility processing 100 samples a week.  
  *Minimum: BIO: 1, PRO: 3*

- **Tool Development:**  
  Creating tools for other bioinformaticians.  
  *Minimum: BIO: 3, PRO: 5*

In larger teams, roles can be more specialized. As a programmer turned bioinformatician, you might do best in larger teams or projects where you’re given clear instructions (e.g. machine learning analysis) rather than roles that require deep biological inference.

---

## 5. Team Structure

- **Small Teams/Startups:**  
  Everyone wears multiple hats. Programmers might even handle design.
  
- **Larger Corporates:**  
  Roles are compartmentalized (project managers, business analysts, etc.). You’ll often get a Jira ticket with “do X analysis on dataset Y” since you might not yet have the experience to decide on the analytical approach.

- **Funding Reality:**  
  Funding generally comes from grants. Lab heads secure money for experiments, and you’ll be analyzing the resulting data from wet lab work.

---

## 6. Essential Skills

### Data Processing
- **Workflow:**  
  Bioinformatics often involves running existing tools and pipelines on large datasets (e.g. a 40 GB FastQ file) and then analyzing the much smaller output (typically under 100 MB).

### Command Line & Scripting
- **Linux Tools:**  
  Building command line tools with Bash and basic scripting is invaluable. You may need to download source code from GitHub and build it via Make.

### Programming Languages
- **Python:**  
  Widely used for data analysis with libraries like Pandas, NumPy, and matplotlib. Use Jupyter Notebook for exploratory work.
- **R:**  
  Excellent for graphing, statistics, and quick analysis. Although less suited for large-scale software development, a few lines of R can handle basic stats and plots.

### Workflow Management
- **Pipelines:**  
  For automated workflows, familiarize yourself with workflow languages like SnakeMake or NextFlow.

---

## 7. Technology and Tools

### Wet Lab Technology
- **Core Techniques:**  
  - PCR  
  - Enrichment (capture and amplification)  
  - High throughput sequencing (Illumina and long-read technologies)

- **Additional Methods:**  
  Get a basic understanding of cell and animal models, western blot, antibodies, immunofluorescence, microarrays, and mass spectrometry.

### Command Line Tools
- **Mapping/Alignment:**  
  E.g., bwa mem.
- **Working with BAM Files:**  
  E.g., samtools.
- **Pipelines:**  
  Look up “variant calling pipeline best practices” or “RNAseq differential expression pipeline” for tutorials on tools like GATK, vardict, STAR aligner, and DeSeq.

### File Formats
- **Key Formats:**  
  - FastQ  
  - BAM (and SAM, the text version)  
  - VCF  
  - BED, GTF, GFF
- **Practice:**  
  Download public datasets, examine files on the command line, and experiment with open-source libraries to iterate over them and perform basic analysis (e.g. counting variant types in a VCF).

---

## 8. Sub-Domains & Specialization

- **Focus Areas:**  
  There are many niches in bioinformatics. If you have expertise in a particular area (e.g. machine learning or image processing), target roles where those skills apply.
  
- **Clinical Emphasis:**  
  Note that most clinical work currently centers on variant calling, though RNAseq is becoming more common.

---

## 9. Building Connections & Engaging with Labs

- **Local Labs:**  
  Survey local university or institutional websites to see what labs are doing. It can be valuable to meet bioinformaticians who’ve transitioned from programming or lab researchers in areas of interest.
  
- **Sample Questions:**  
  - “If someone was joining your lab and could read one review paper to get up to speed, what would it be?”
  - “Can you recommend a paper that demonstrates the technology/assay/analysis you use?”
  - “Which Wikipedia page for one disease and five genes should I read to understand your lab’s focus?”

- **Networking:**  
  Joining bioinformatics Slack channels and attending local bioinfo talks can help you build connections and learn about opportunities.
  
- **Free Analysis Offer:**  
  Some labs have unprocessed data. Offering to analyze this data—while being aware that you might be seen as a student—can be a way to get your foot in the door.

---

## 10. Building a Resume

- **Tailor Your Skills:**  
  Customize your resume based on the jobs available. For clinical roles, emphasize human variant calling; for agricultural research, show knowledge in that area.
  
- **Portfolio:**  
  Maintain a GitHub account to showcase your projects. Contributing to open-source tools (fixing bugs, adding features) demonstrates both technical skill and teamwork. Make sure you understand the code you modify and include unit tests.

---

## 11. Further Reading

- [I Should Have Loved Biology](https://jsomers.net/i-should-have-loved-biology/)
- [Farewell to Bioinformatics](https://madhadron.com/science/farewell_to_bioinformatics.html)
