# Processing, Analysis and Visualization

## Cosmos

[![](https://img.shields.io/badge/FIWARE-Processing\Analysis-88a1ce.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

* [Git Repository](https://github.com/telefonicaid/fiware-cosmos)
* [Documentation](https://fiware-cosmos-flink.readthedocs.io)

### What is Cosmos?

The BigData Analysis GE is intended to deploy means for analyzing both batch and stream data (in order to get, in the end, insights on such a data).

The batch part has been widely developed throught the adoption and/or the in-house creation of the following tools:
* A Big Data As A Service engine, either the ''official'' one based on Openstack's Sahara, either the light version based on kubernetes cluster.
* This provides
* Hadoop
* Spark Scala
* Apache Flink

The batch part is enriched with the following tools, that conform the so-called Cosmos Ecosystem:
* Cygnus, a tool for connecting Orion Context Broker with several data storages, HDFS and STH (see below) included, in order to create context data historics.
* STH Comet, a MongoDB context data storage for short-term historic.
The fast data (streaming)  part allows an state of the art solution.
* We provide an apache Flinck connector ( https://github.com/sonsoleslp/fiware-cosmos-orion-flink-connector ) you can follow some examples here ( https://github.com/sonsoleslp/fiware-cosmos-orion-flink-connector-examples )


This project is part of [FIWARE](http://fiware.org/) and has been rated as follows:

* **Version Tested:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Version&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.version&colorB=blue)
* **Documentation:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Completeness&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.docCompleteness&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Usability&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.docSoundness&colorB=blue)
* **Responsiveness:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Respond&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.timeToCharge&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Fix&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.timeToFix&colorB=blue)
* **FIWARE Testing:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Tests%20Passed&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.failureRate&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Scalability&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.scalability&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Performance&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.performance&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Stability&url=https://fiware.github.io/catalogue/json/cosmos.json&query=$.stability&colorB=blue)



## Knowage

[![](https://img.shields.io/badge/FIWARE-Visualization-88a1ce.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

* [Git Repository](https://github.com/KnowageLabs/Knowage-Server)
* [Docker Hub](https://hub.docker.com/r/fiware/knowage-server-docker/)
* [Documentation](http://knowage.rtfd.io/)

### What is Knowage?
Knowage is the professional open source suite for modern business analytics over traditional sources and big data systems.

Knowage is the new generation of open source analytical solution, as a natural evolution of the well known SpagoBI. Based on open standards and with a modular offering, Knowage addresses specific domains to particular sub-products, that can be combined each other to get a tailored size in a single solution. The sub-products of the suite are:

* BD (big data), to analyse data stored on big data clusters or NoSQL databases
* SI (smart intelligence), the usual business intelligence on structured data, but more oriented to self-service capabilities and agile prototyping
* ER (enterprise reporting), to produce and distribute static reports
* LI (location intelligence), to relate business data with spatial or geographical information
* PM (performance management), to manage KPIs and organize scorecards
* PA (predictive analysis), for more advanced analyses
* EI (embedded intelligence), to link Knowage with external solutions provided by the customer or third parties.

The released packages contain all sub-products combined togheter into an unique and complete data analytics solution.
Knowage answers to a more modern vision of the data analytics, providing advanced self-service capabilities that give autonomy to the end-user, now able to build his own analysis and explore his own data space, also combining data that come from different sources.

### Why use Knowage?

Knowage suite provides full capabilities to get insights on data and turn them into actionable knowledge for effective decision-making processes. It includes not only usual reporting and charting tools, but also innovative solutions for emerging domains, such as location intelligence, KPIs, real-time, mobile, big data, data mining, what-if, interactive cockpits and self-service capabilities. Its modular approach, scalable architecture and open standards ensure easy customization and the development of user-friendly solutions. Visit www.knowage-suite.com for more details.

This project is part of [FIWARE](http://fiware.org/) and has been rated as follows:

* **Version Tested:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Version&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.version&colorB=blue)
* **Documentation:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Completeness&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.docCompleteness&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Usability&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.docSoundness&colorB=blue)
* **Responsiveness:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Respond&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.timeToCharge&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Fix&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.timeToFix&colorB=blue)
* **FIWARE Testing:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Tests%20Passed&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.failureRate&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Scalability&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.scalability&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Performance&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.performance&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Stability&url=https://fiware.github.io/catalogue/json/knowage.json&query=$.stability&colorB=blue)

## Wirecloud

* [Git Repository](https://github.com/Wirecloud/wirecloud)
* [Docker Hub](https://hub.docker.com/r/fiware/wirecloud/)
* [Documentation](https://https://wirecloud.rtfd.io/)


### What is Wirecloud

[![](https://img.shields.io/badge/FIWARE-Visualization-88a1ce.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

Wirecloud builds on cutting-edge end-user development, RIA and semantic technologies to offer a next-generation end-user centred web application mashup platform aimed at leveraging the long tail of the Internet of Services.

Wirecloud builds on cutting-edge end-user (software) development, RIA and semantic technologies to offer a next-generation end-user centred web application mashup platform aimed at allowing end users without programming skills to easily create web applications and dashboards/cockpits (e.g. to visualize their data of interest or to control their domotized home or environment). Web application mashups integrate heterogeneous data, application logic, and UI components (widgets) sourced from the Web to create new coherent and value-adding composite applications. They are targeted at leveraging the "long tail" of the Web of Services (a.k.a. the Programmable Web) by exploiting rapid development, DIY, and shareability. They typically serve a specific situational (i.e. immediate, short-lived, customized) need, frequently with high potential for reuse. Is this "situational" character which precludes them to be offered as 'off-the-shelf' functionality by solution providers, and therefore creates the need for a tool like Wirecloud

Note: Wirecloud is at the core of the FIWARE infrastructure and is therefore intended to be installed by FIWARE platform providers when setting up a configuring a new instance of the FIWARE instance node. It is not intended to be deployed/configured by a developer. Developers are encouraged to use the global instance of Wirecloud provided in the FIWARE Lab. Nevertheless, we provide an installer for stand-alone instances of Wirecloud, along with recipes and blueprints to install it in the Cloud portal (using the PaaS Manager), and the corresponding installation guides.

### Why use Wirecloud

Web application mashups can be manually developed using conventional web programming technologies (e.g. see http://programmableweb.com). But this fails to take full advantage of the approach. Mashup tools and platforms like Wirecloud aim at development paradigms that do not require programming skills and, hence, target end users, being them citizens, knowledge workers, portal designers, etc.

By using Wirecloud you have access to the following key features:

* Innovate through experimentation by choosing the best suited widgets, operators and prefab mashup-lets for your devised mashup from a vast, ever-growing distributed catalogue
* The wiring editor allows you to easily connect widgets in a mashup to create a full-fledged dashboard with RIA functionality
* The piping editor allows you to easily connect widgets to back-end services or data sources through an extendable set of operators, including filters, aggregators, adapters, etc.
* Share your newly created mashup with other colleagues and users. Comment it, tag it and rate it to foster discoverability and shareability
* Help to build a strong community by commenting, tagging and rating others' widgets, operators and mashups. The platform will also do its best to complement your contribution

More information available at the Wirecloud website: https://conwet.fi.upm.es/wirecloud

This project is part of [FIWARE](http://fiware.org/) and has been rated as follows:

* **Version Tested:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Version&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.version&colorB=blue)
* **Documentation:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Completeness&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.docCompleteness&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Usability&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.docSoundness&colorB=blue)
* **Responsiveness:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Respond&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.timeToCharge&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Fix&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.timeToFix&colorB=blue)
* **FIWARE Testing:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Tests%20Passed&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.failureRate&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Scalability&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.scalability&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Performance&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.performance&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Stability&url=https://fiware.github.io/catalogue/json/wirecloud.json&query=$.stability&colorB=blue)


## Kurento

[![](https://img.shields.io/badge/FIWARE-Media_Streams-4f3495.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

* [Git Repository](https://github.com/Kurento/kurento-media-server)
* [Docker Hub](https://hub.docker.com/r/fiware/stream-oriented-kurento/)
* [Documentation](https://kurento.rtfd.io/)

### What is Kurento?
The Stream Oriented GE is a development framework that provides an abstraction layer for multimedia capabilities, allowing non-expert developers to include interactive media components to their applications. At the heart of this enabler there is the Open API. A REST-like API, based on JSON RPC 2.0, exposing a toolbox of Media Elements that can be chained to create complex media processing pipelines. The Stream Oriented GE provides several client implementations of the Open API. The Java client allows developers to include media capabilities to Java or JEE applications. There is also a Javascript client ready to be used with NodeJS or directly in browser applications. Thanks to these, the Stream Oriented GE provides developers with a set of robust end-to-end interoperable multimedia communication capabilities to deal with the complexity of transport, encoding/decoding, processing and rendering tasks in an easy and efficient way.

### Why use Kurento?

The development of interactive multimedia applications is a complex task, which usually requires specific expertise and huge investments. Stream Oriented GE brings a number of abstractions and enablers democratizing multimedia technologies and making possible to any WWW developer to create powerful applications involving advanced features such as: interoperable audiovisual communications, computer vision, augmented reality, flexible media playing, recording, etc. The Stream Oriented GE will be particularly useful and intuitive for developers familiar with Java EE and JavaScript technologies, although its capabilities are also exposed through agnostic interoperable network interfaces that can be consumed from any other language of system. In a nutshell, It makes possible the development of complex interactive multimedia communications in a fast, simple and easy way.

This project is part of [FIWARE](http://fiware.org/) and has been rated as follows:

* **Version Tested:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Version&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.version&colorB=blue)
* **Documentation:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Completeness&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.docCompleteness&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Usability&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.docSoundness&colorB=blue)
* **Responsiveness:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Respond&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.timeToCharge&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Fix&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.timeToFix&colorB=blue)
* **FIWARE Testing:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Tests%20Passed&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.failureRate&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Scalability&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.scalability&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Performance&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.performance&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Stability&url=https://fiware.github.io/catalogue/json/kurento.json&query=$.stability&colorB=blue)

---

## :new: Perseo (Incubated)

[![](https://img.shields.io/badge/FIWARE-Processing\Analysis-88a1ce.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

**Core**

* [Git Repository](https://github.com/telefonicaid/perseo-core/)
* [Docker Hub](https://hub.docker.com/r/telefonicaiot/perseo-core/)
* [Documentation](https://github.com/telefonicaid/perseo-fe/tree/master/documentation)

**Front-End**

* [Git Repository](https://github.com/telefonicaid/perseo-fe/)
* [Docker Hub](https://hub.docker.com/r/telefonicaiot/perseo-fe/)
* [Documentation](https://github.com/telefonicaid/perseo-fe/tree/master/documentation)

### What is Perseo?

The Perseo Context-aware Complex Event Processing (Context-aware CEP) GE is a module that listens to events from context data (coming from Orion Context Broker or any other NGSI-compliant system or service) in real-time, and generates immediate insight, enabling thus instant response to changing conditions

### Why use Perseo?

Event processing in a Smart Solution enables you to listen to changes in the incoming context data and identify patterns in order to react by triggering external actions (e.g sending eMails or SMS messages)

Perseo is an NSGI compliant rules-based query engine for event processing based on Esper CEP which means that rules can be defined using SQL-like queries in EPL eliminating the need to write code to hard-wire event conditions. Therefore Perseo can act as a bridge between the context data and other external systems.






## :arrow_upper_right: Fog Flow (Incubated)

[![](https://img.shields.io/badge/FIWARE-Processing\Analysis-88a1ce.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

* [Git Repository](https://github.com/smartfog/fogflow)
* [Documentation](https://fogflow.rtfd.io/)

### What is Fog Flow?

FogFlow is an IoT edge computing framework to orchestrate dynamic processing flows over cloud and edges. It can dynamically and automatically composite multiple NGSI-based data processing tasks to form high level IoT services, and then orchestrate and optimize the deployment of those services within a shared cloud-edge environment, with regards to the availability, locality, and mobility of IoT devices.

### Why use Fog Flow?

The cost of a cloud-only solution is too high to run a large scale IoT system with >1000 geo-distributed devices
many IoT services require fast response time, such as <10ms end-to-end latency
service providers are facing huge complexity and cost to fast design and deploy their IoT services in a cloud-edge environment - business demands are changing fast over time and service providers need to try out and release any new services over their shared cloud-edge infrastructure at a fast speed
lack of programming model to fast design and deploy IoT services over geo-distributed ICT infrastructure
lack of interoperability and openness to share and reuse data and dervied results across various applications

This project is part of [FIWARE](http://fiware.org/) and has been rated as follows:

* **Version Tested:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Version&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.version&colorB=blue)
* **Documentation:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Completeness&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.docCompleteness&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Usability&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.docSoundness&colorB=blue)
* **Responsiveness:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Respond&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.timeToCharge&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Fix&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.timeToFix&colorB=blue)
* **FIWARE Testing:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Tests%20Passed&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.failureRate&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Scalability&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.scalability&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Performance&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.performance&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Stability&url=https://fiware.github.io/catalogue/json/fogflow.json&query=$.stability&colorB=blue)


## :arrow_upper_right: AEON (Incubated)

[![](https://img.shields.io/badge/FIWARE-Processing\Analysis-88a1ce.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAVCAYAAAC33pUlAAAABHNCSVQICAgIfAhkiAAAA8NJREFUSEuVlUtIFlEUx+eO+j3Uz8wSLLJ3pBiBUljRu1WLCAKXbXpQEUFERSQF0aKVFAUVrSJalNXGgmphFEhQiZEIPQwKLbEUK7VvZrRvbr8zzjfNl4/swplz7rn/8z/33HtmRhn/MWzbXmloHVeG0a+VSmAXorXS+oehVD9+0zDN9mgk8n0sWtYnHo5tT9daH4BsM+THQC8naK02jCZ83/HlKaVSzBey1sm8BP9nnUpdjOfl/Qyzj5ust6cnO5FItJLoJqB6yJ4QuNcjVOohegpihshS4F6S7DTVVlNtFFxzNBa7kcaEwUGcbVnH8xOJD67WG9n1NILuKtOsQG9FngOc+lciic1iQ8uQGhJ1kVAKKXUs60RoQ5km93IfaREvuoFj7PZsy9rGXE9G/NhBsDOJ63Acp1J82eFU7OIVO1OxWGwpSU5hb0GqfMydMHYSdiMVnncNY5Vy3VbwRUEydvEaRxmAOSSqJMlJISTxS9YWTYLcg3B253xsPkc5lXk3XLlwrPLuDPKDqDIutzYaj3eweMkPeCCahO3+fEIF8SfLtg/5oI3Mh0ylKM4YRBaYzuBgPuRnBYD3mmhA1X5Aka8NKl4nNz7BaKTzSgsLCzWbvyo4eK9r15WwLKRAmmCXXDoA1kaG2F4jWFbgkxUnlcrB/xj5iHxFPiBN4JekY4nZ6ccOiQ87hgwhe+TOdogT1nfpgEDTvYAucIwHxBfNyhpGrR+F8x00WD33VCNTOr/Wd+9C51Ben7S0ZJUq3qZJ2OkZz+cL87ZfWuePlwRcHZjeUMxFwTrJZAJfSvyWZc1VgORTY8rBcubetdiOk+CO+jPOcCRTF+oZ0okUIyuQeSNL/lPrulg8flhmJHmE2gBpE9xrJNkwpN4rQIIyujGoELCQz8ggG38iGzjKkXufJ2Klun1iu65bnJub2yut3xbEK3UvsDEInCmvA6YjMeE1bCn8F9JBe1eAnS2JksmkIlEDfi8R46kkEkMWdqOv+AvS9rcp2bvk8OAESvgox7h4aWNMLd32jSMLvuwDAwORSE7Oe3ZRKrFwvYGrPOBJ2nZ20Op/mqKNzgraOTPt6Bnx5citUINIczX/jUw3xGL2+ia8KAvsvp0ePoL5hXkXO5YvQYSFAiqcJX8E/gyX8QUvv8eh9XUq3h7mE9tLJoNKqnhHXmCO+dtJ4ybSkH1jc9XRaHTMz1tATBe2UEkeAdKu/zWIkUbZxD+veLxEQhhUFmbnvOezsJrk+zmqMo6vIL2OXzPvQ8v7dgtpoQnkF/LP8Ruu9zXdJHg4igAAAABJRU5ErkJgggA=)](https://www.fiware.org/developers/catalogue/)

* [Git Repository](https://github.com/atos-ari-aeon)
* [Documentation](https://aeon-platform.rtfd.io/)

### What is AEON?

The Cloud Messaging GE (AEON) provides cloud services (channels) to communicate an unlimited number of entities, interchanging an unlimited amount of information. But it is not only about the communication, it also provides services for easily management of entities participating in your environments: mobile, truck, box, thermometer, even yourself...).
The Cloud Messaging GE support two main operation blocks:

Resources Management: Management of the different entities and channels.
Create, Remove, Update and Delete Entities
Create, Remove, Update and Delete Channels associated to an entity
Publish/Subscribe: Based on managing the publish and subscribe operations.
Publish information over a channel.
Subscribe to a channel. Pause, continue and stop the subscription getting a better control on your operations.
The Cloud Messaging GE offers, not only and API to mange all the resources but also it provides different SDKs to start using it by just including it in your code.

### Why use AEON?

Each time that you need to develop an application with communication needs, Cloud Messaging GE should be included. It is very difficult to set up a communication environment and it is time you loose on what really matters, develop the main functionalities of your applications. Therefore, Cloud Messaging solves this problem for you, allowing you to focus on your domain. E,g. If you want to develop an application that updates the status of a delivered package in real-time, with a few lines of code, you can update this status from the mobile terminal to the transport operator's back-office.

This project is part of [FIWARE](http://fiware.org/) and has been rated as follows:

* **Version Tested:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Version&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.version&colorB=blue)
* **Documentation:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Completeness&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.docCompleteness&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Usability&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.docSoundness&colorB=blue)
* **Responsiveness:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Respond&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.timeToCharge&colorB=blue) ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Time%20to%20Fix&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.timeToFix&colorB=blue)
* **FIWARE Testing:** ![ ](https://img.shields.io/badge/dynamic/json.svg?label=Tests%20Passed&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.failureRate&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Scalability&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.scalability&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Performance&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.performance&colorB=blue)
![ ](https://img.shields.io/badge/dynamic/json.svg?label=Stability&url=https://fiware.github.io/catalogue/json/aeon.json&query=$.stability&colorB=blue)

