# Diving deep into the Panama Papers

# Files
- Project_main: Project analysis notebook
- Project_report: Project report pdf

# Abstract
The Panama Papers are arguably the largest leak of confidential data to date. They provide a wealth of knowledge by exposing previously hidden ties between corporations and their ecosystem.  This paper presents a social network analysis of the companies and individuals involved in this leak. We identified the countries in which the key players were operating, how we could predict the involvement of a country and what were the underlying relationships between the parties involved. We were able to shed light on the central actors of the network and provide further investigations on their connections.

# Introduction
The Panama Papers are leaked documents that detail the internal operations of one of the world's biggest firms in incorporation of offshore entities, Mossack Fonseca. This Panamanian law firm and corporate service provider had financial and attorney-client information for more than 210 000 offshore entities revealed to the public. While offshore business entities are legal, reporters found that some of the Mossack Fonseca shell corporations were used for illegal purposes, namely fraud, tax evasion, and evading international sanctions. Therefore one may argue that it is of public and state interest to explore the Panama Papers in order to extract insights about the key players involved. We intend to discover, analyse and explain the underlying relationships inside the Panama Papers.

# Research questions
What are the key figures about the evolution of Mossack Fonseca's clients at different scales over the span of 40 years ? How can we put these figures into historical (economy, laws, policies...) context ?  
- What are the jurisdictions and countries with the most offshore entities ? Is the number of entities linked to the number of intermediaries and officers ?  
- What is the evolution of the number of incorporated offshore companies for the last 50 years ? How does one explain it based on historical events ?  
  
Is there a link between economic and financial indicators and the involvement of a country ? That is what are the main correlates of evasion ?  
- Predict the involvement of a country based on financial and risk indicators. That is, find the correlates of evasion and discuss the relevance of commonly used metrics by regulators.  
  
What are the insights we may extract from a social network analysis of the Panama Papers using a top down approach ? What about a specific country analysis ?    
- Who are the key actors ? How can we quantify someone's importance in the papers ?  
- Is the network a small world ?  
- What is the shape of the network ? Is it organized in communities ?  
- Who are the principal players in specific countries ?  
  
# Dataset
We will use the ICIJ Offshore Leaks Panama Papers Dataset found at: https://www.occrp.org/en/panamapapers/database  
The dataset has been made available as 5 CSV files.  
We will also resort to additional data sources about countries economy, laws and policies for the last 50 years (links in notebook).

# A list of internal milestones up until project milestone 2
Load Dataset-Done  
Preliminary Data inspection-Done  
Preliminary Data transformation-Done  
Enitity key figures-Done  
Intermediary key figures-Done  
Officer key figures-Done  
Nodes population relationship-Done  
Put key figures into historical context-Done  
Load Dataset as a Network-Done    
What's next for Milestone 3 (i.e network analysis, specific country analysis, correlates of evasion)-Done

# A list of internal milestones up until project milestone 3
Basic network statistics-Done  
Network connected components-Done   
Network clustering and density-Done  
Is the network a small world-Done  
Overall degree distribution-Done  
Degree distribution per node type-Done  
Is the degree distribution a power law-Done  
Network pagerank-Done  
Extract specific country ego graph-Done  
Centrality measures-Done  
Community extraction-Done  
Communities visualization-Done 
Investigation of countries-Done  
Loading financial indicators data-Done 
Cleaning financial indicators data-Done  
Correlates of evasion analysis-Done  
Correlates of evasion results-Done  

# Contributions
Franck: Third research question with focus on specific countries analysis. Report. Poster.  
Cris: Second research question. Report.  
Vincent: First research question and third research question with focus on full network analysis. Report. Presentation.  
