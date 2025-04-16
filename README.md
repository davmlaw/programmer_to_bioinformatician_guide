# How to Get a Job as a Bioinformatician as a Programmer

My personal tips to enter the field. I worked as a professional programmer for 7 years (mostly Java) before starting as a bioinformatician in 2011

## 1. Job Market

- **Limited Opportunities:**  
  Bioinformatics jobs are far fewer than general programming jobs. You’ll likely need to work harder, learn more, and may face lower pay and job security.
  
- **Upsides:**  
  You get more interesting work, greater freedom, and potentially higher job satisfaction.

## 2. Learning Resources

### Project Rosalind
- **What Is It?**  
  Think of it as “LeetCode for bioinformatics.” Check out the Bioinformatics Stronghold section at [Project Rosalind](https://rosalind.info/problems/list-view/).
- **Why Use It?**  
  It’s a fun way to learn biology basics and improve your skills. The challenges start easy and ramp up in difficulty. If you don’t find it engaging, bioinformatics might not be for you.

### Basic Molecular Biology
- **Learning the Fundamentals:**  
  Biology may seem full of memorization, but its core concepts—cells, genetics, DNA, RNA, and proteins—are accessible.
- **Resources:**  
  - WEHI animations: [WEHI Animations](https://www.wehi.edu.au/tv-content-type/animations/)
  - Start with a second-hand first-year textbook on biology (covering cells and intro genetics) and then skim a more advanced genetics book.
- **Key Terms:**  
  Familiarize yourself with nucleus, chromatin, transcription factors, DNA polymerase, exons, splicing, mRNA, transcription, ribosomes, and protein complexes.

## 3. Bio vs. Informatics Trade-Offs

There are three primary entry points:

1. **Train as a Bioinformatician:** (Masters, PhD)
2. **Train as a Biologist and Learn to Code:** (Masters, PhD in biology, then develop coding skills)
3. **Programmer with Self-Education in Biology:** (Bachelor’s plus self-study)

Think of it like role-playing stats of 3 skills: Biology (BIO), Programming (PRO) and Bioinformatics tools, technology and file formats (TOOL).

Some made up people could have:

| Profile                                               | BIO | PRO | TOOL |
|-------------------------------------------------------|-----|-----|------|
| **PhD Biologist with 6 months self-taught programming** | 7   | 1   | 2    |
| **Masters Bioinformatician**                          | 4   | 4   | 6    |
| **Professional Programmer (no biology background)**   | 0   | 8   | 0    |
| **Programmer with 2 months self-education**  | 1   | 8   | 2    |

When hiring, you are generally trading off skills in 1 area vs another, as you can't afford someone with maxed out stats!

## 4. Bioinformatics roles

Thinking about the skill tradeoffs, some jobs have a minimum skills, eg (made up examples):

- **Individual Analyses for a Lab:**  
  A lab might perform a standard DNA sequencing assay (variant calling, RNAseq, ChiPseq) and then use mapping, QC, and analysis to produce spreadsheets/graphs.  
  *Minimum: BIO: 5, PRO: 1, TOOL: 2*

- **Building Automated Pipelines:**  
  Example: A genomics facility processing 100 samples a week.  
  *Minimum: BIO: 1, PRO: 2, TOOL: 5*

- **Tool Development:**  
  Creating a new tool for other bioinformaticians.  
  *Minimum: BIO: 3, PRO: 3, TOOL: 4*.

- **Tool Optimisation:**  
  Making an existing tool run faster, e.g. rewriting an existing script into a fast polished tool   
  *Minimum: BIO: 1, PRO: 6, TOOL: 1*


## 5. Team Structure

In smaller teams, everyone has to wear multiple hats, eg programmers in a startup may handle design, while in larger teams there is more division of roles (project manager, business analyist etc)

In larger teams, roles can be more specialized. As a programmer turned bioinformatician, you might do best in larger teams or projects where you’re given clear instructions rather than roles that require deep biological inference.

As you gain more experience, you can start to come up with your own ideas, and chase what you find interesting. But it usually takes quite a few years until you know where you can do novel interesting work (eg how can I use a new technique to solve a useful problem better/faster than anyone else)

### Sole Bioinformatician

- **Funding and Environment:**  
  Funding generally comes from grants. Lab heads secure the funds for experiments, and you’ll be analyzing the resulting data from wet lab work.
- **Roles and Responsibilities:**  
  In this setting, the lab head acts as the project manager, setting the overall scientific vision, while a lead author (often a postdoc) functions like a business analyst by providing high-level directives—typically along the lines of, "apply a similar analysis as in this paper to our data." However, detailed technical guidance is usually lacking.
- **Downsides:**  
  Lack of in-house support. Without other bioinformaticians to consult, you may find yourself isolated, missing out on the opportunity to share ideas, learn new techniques, and receive mentorship.
- **Recommendations:**  
  If you end up as the sole bioinformatician, prioritize reaching out beyond your organization. Attend local talks, join online communities, and build a network with other bioinformaticians to enhance your skills and receive peer support.

### Bioinformatician in a Large Team or Facility

- **Structured Environment:**  
  Larger teams or facilities usually have a clearer organizational structure, with defined roles and workflow processes.
- **Mentorship and Guidance:**  
  In these settings, a senior bioinformatician or technical lead is often available to provide advice and guidance, allowing you to refine your skills and even take on more niche roles.
- **Specialization Opportunities:**  
  The structure allows for role specialization—for example, focusing on building automated pipelines, developing new tools, or performing advanced data analysis—so you can deepen expertise in your chosen area.
- **Team Support and Collaboration:**  
  With more colleagues in the mix, you benefit from regular team meetings, in-house training, and collaborative troubleshooting, which not only accelerates learning but also helps spread best practices across projects.
  
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

## 8. Sub-Domains & Specialization

- **Focus Areas:**  
  There are many niches in bioinformatics. If you have expertise in a particular area (e.g. machine learning or image processing), target roles where those skills apply.
  
- **Clinical Emphasis:**  
  Note that most clinical work currently centers on variant calling, though RNAseq is becoming more common.

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

## 10. Building a Resume

- **Tailor Your Skills:**  
  Customize your resume based on the jobs available. For clinical roles, emphasize human variant calling; for agricultural research, show knowledge in that area.
  
- **Portfolio:**  
  Maintain a GitHub account to showcase your projects. Contributing to open-source tools (fixing bugs, adding features) demonstrates both technical skill and teamwork. Make sure you understand the code you modify and include unit tests.

## 11. Further Reading

- [I Should Have Loved Biology](https://jsomers.net/i-should-have-loved-biology/) - biology from a programming point of view
- [Farewell to Bioinformatics](https://madhadron.com/science/farewell_to_bioinformatics.html) - for an alternative view - someone who left bioinformatics to work on programming
