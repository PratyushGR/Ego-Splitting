# Network_science_final_project

## Project:
Ego-splitting Framework in C++

## Project Type:
Implementation-flavor 

## Paper Link:
https://dl.acm.org/doi/10.1145/3097983.3098054 

## Code Implementation :
C++ 

## Group: 9

## Contrubutors:
Raj Indroju, Sai Krishna Reddy Kandhadi, Pratyush Reddy Gaggenapalli, Dinesh Kumar Pullepally

## Github URL: 
https://github.com/PratyushGR/Network_science_final_project.git

# Input DataSets: 

Data sets are provided int the Inputs directory we have tested our source code on 4 different datasets
<img width="641" alt="image" src="https://user-images.githubusercontent.com/99221826/205421753-4be3ed68-9fc0-49fb-aa87-d25cf8d5b277.png">

## a. Test
This is small graph authors have used to explain the framework in the research paper.  Graph with 9 nodes and 11 edges. 
<img width="236" alt="image" src="https://user-images.githubusercontent.com/99221826/205421936-d49ae0aa-cccc-4354-b06a-4e2fb6494c59.png">
			
	
## b. Tv_show edges
Data collected about Facebook pages (November 2017). These datasets represent blue verified Facebook page networks of different categories. Nodes represent the pages and edges are mutual likes among them.
<img width="512" alt="image" src="https://user-images.githubusercontent.com/99221826/205421909-281df20d-187b-45a0-8243-42f26b399a58.png">


## c. DBLP
The DBLP computer science bibliography provides a comprehensive list of research papers in computer science. We construct a co-authorship network where two authors are connected if they publish at least one paper together. Publication venue, e.g, journal or conference, defines an individual ground-truth community; authors who published to a certain journal or conference form a community. We regard each connected component in a group as a separate ground-truth community. We remove the ground-truth communities which have less than 3 nodes. We also provide the top 5,000 communities with highest quality which are described in our paper. As for the network, we provide the largest connected component.
<img width="317" alt="image" src="https://user-images.githubusercontent.com/99221826/205421895-9eac5ffd-d944-4c2a-afec-a35714531537.png">

## tester_edges
This is small graph authors have used to explain the framework in the research paper.  Graph with 10 nodes and 28 edges. 

# Code Execution
we have implemented our project in C++ from scratch and we have not used any complex libraries any cpp compiler with right configuration would be able to run our script.

###### please follow the below steps before executing the script
# step1:
Set correct Input file path to "file_name" variable in the main function in ego_split.cpp file in order to execute our algorithm on the provided data set and plot get the desired splitted ego's for each node

<img width="398" alt="image" src="https://user-images.githubusercontent.com/99221826/205422118-fb213d42-4415-4456-87e8-c6ebd7ab9d8d.png">

# step2:
Excecute the e









