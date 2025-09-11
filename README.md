<img width="879" height="625" alt="image" src="https://github.com/user-attachments/assets/b1204776-1085-4d67-a925-f0ac48e497b3" />

##sketch1+2+3

## Sketch 1: Portraits of Power (Bipartite Network)

**Questions**: Who were the figures most represented in the Revolutionary era? Do the same leaders appear both in museum collections (portraits, artifacts) and in newspapers of the time?  

**Data**:  
- collection dataset: `indexed_names` (museum portraits, sitters, artists)  
- LOC Newspapers: frequency of names in `ocr_text`  

**Visualization**: Bipartite network graph linking museum figures (left) and newspaper figures (right).  


## Sketch 2: Objects Over Time (Stacked Area Chart)

**Questions**: How did the types of objects (paintings, quilts, decorative arts) shift over the years 1770–1810? Did some categories become more prominent after independence?  

**Data**:  
- collection dataset: `indexed_dates`, `indexed_object_types`  

**Visualization**: Stacked area chart showing changes in counts of object types over time.  


## Sketch 3: Soldiers and Support (Choropleth Map)

**Questions**: Which states submitted the most Revolutionary War pension and bounty land applications? Are there geographic patterns in postwar veteran support?  

**Data**:  
- National Archives dataset: `title` + `ocrText` (state locations from pension files)  

**Visualization**: Choropleth map of the U.S., shading states by number of applications.  


