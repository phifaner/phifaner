---
title: "Column-oriented In Memory Spatial Database based on GPU"
collection: projects
type: "Research"
permalink: projects/2016-sesame-gpudb
venue: "National University of Singapore"
date: 2016-08-01~2018-01-01
location: "Singapore"
---

Interactive visual data exploration requires an instant response to a user's request. The state-of-the-art database systems rarely satisfy such a requirement in dealing with massive data. A few research have be pioneering at GPU databases and compile SQL queries to native GPU code with the LLVM compiler framework, such as OmnisciDB, PG-Strom, and BlazingDB. These databases allow customers to leverage supercomputer processing power to deliver SQL-powered interactive analytics upon hundreds of billions of pieces of data.

This project aims at building a column-oriented database for interactive exploring spatial data. To this end, storing, indexing, optimization, and querying are developed using CUDA. Since users usually explore relationships among hundreds of dimension, we propose a novel index to speedup range queries by leveraging fast joins on GPU. The performance is 14 times faster than spark, and 4 times faster than OmnisciDB. We also build a visual analytics system to support flexible interactions and analysis on map using D3.js and Mapbox.


Technical Stack
======
C++, CUDA, python, ReactJS, Mapbox, websocket

Teams
======
4 members

<img src='../images/tokyo-keyword-spatial.png'>(https://drive.google.com/file/d/1ktc1zWU27Vql_2vCjLZC_cHiMoKzeT_j/view?usp=sharing)

