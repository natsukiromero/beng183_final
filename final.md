# 35 FASTQC: Quality Check of RNAseq Reads
1. [Background](#351)
2. [QC Report Analysis Modules](#352)<br>
	2.1. [Basic Statistics](#3521)<br>
	2.2. [Per Base Sequence Quality](#3522)<br>
	2.3. [Per Tile Sequence Quality](#3523)<br>
	2.4. [Per Sequence Quality Scores](#3524)<br>
	2.5. [Per Base Sequence Content](#3525)<br>
	2.6. [Per Sequence GC Content](#3526)<br>
	2.7. [Per Base N Content](#3527)<br>
	2.8. [Sequence Length Distribution](#3528)<br>
	2.9. [Sequence Duplication Levels](#3529)<br>
	2.10. [Overrepresented Sequences](#35210)<br>
	2.11. [Adapter Content](#35211)<br>

## 35.1 Background<a name="351"></a>

Quality assessment of raw reads is the first and very crucial step in the RNAseq analysis pipeline. FastQC is one of the widely used tools to evaluate the quality of high throughput sequencing data. Developed by Simon Andrews at the Babraham Institute, FastQC was developed to address the vast amount of sequencing data produced from NGS in a fast and comprehensive manner. 

FastQC takes a FASTQ file, and analyzes it to generate an easily interpretable report based on a variety of metrics, including sequence quality scores, sequence length distribution, GC content, sequence duplication levels, and the presence of overrepresented sequences or adapter contamination.

FastQC is extremely significant as it allows scientists to identify issues within their data such as poor quality bases, and make decisions about pre-processing steps like data trimming with FastP. This ensures we have high quality data, which is very important for downstream analysis.

Some examples of current tools that extend from or are similar to FastQC are PRINSEQ and MultiQC. 

## 35.2 QC Report Analysis Modules<a name="352"></a>
fastqc generates a final report in a .html file, which can be opened with any browser. Looking through this report, we can read the analysis modules and their metrics to assess the quality of our sequencing data.

The report starts with a summary of the modules, each with an icon to represent their status as “PASS,” “WARNING,” or “FAIL.” The “WARNING” and “FAIL” flags are not meant to be taken at face value, rather noted as a sign to take a closer look at that module.

### 1) Basic Statistics<a name="3521"></a>
### 2) Per Base Sequence Quality<a name="3522"></a>
### 3) Per Tile Sequence Quality<a name="3523"></a>
### 4) Per Sequence Quality Scores<a name="3524"></a>
### 5) Per Base Sequence Content<a name="3525"></a>
### 6) Per Sequence GC Content<a name="3526"></a>
### 7) Per Base N Content<a name="3527"></a>
### 8) Sequence Length Distribution<a name="3528"></a>
### 9) Sequence Duplication Levels<a name="3529"></a>
### 10) Overrepresented Sequences<a name="35210"></a>
### 11) Adapter Content<a name="35211"></a>
