# **Malaria Blood Smear Images**

## **Repository Description**

Computer-aided diagnosis uses computers and computational tools to analyze and evaluate medical data for diagnosing diseases. Recent advances in research have demonstrated the use of computer-aided diagnosis methods for diagnosing diseases. This repository contains all available malaria blood smear image datasets. It is a one-stop shop for researchers and developers working on malaria detection and diagnosis. These datasets were obtained by carrying out a systematic review of papers published between 2013 and 2023 on automated malaria diagnosis.



<style>
.node circle {
  fill: #fff;
  stroke: steelblue;
  stroke-width: 3px;
}

.node text {
  font: 12px sans-serif;
}

.link {
  fill: none;
  stroke: #ccc;
  stroke-width: 2px;
}

</style>

<div id="graph"></div>

<!-- load the d3.js library -->	
<script src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.17/d3.min.js"></script>

<script>

  var treeData = [
    {
      "name": "Blood Smear Images",
      "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/",
      "parent": "null",
      "children": [
        {
          "name": "Access",
          "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Open_Access/",
          "parent": "Blood Smear Images",
          "children": [
	    {
              "name": "Open Access",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Open_Access/Thick&Thin-OA.html",
              "parent": "Access",
              "children": null
            },
            {
              "name": "Controlled Access",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Open_Access/Thick-OA.html",
              "parent": "Access",
              "children": null
            },
        
          ]
        },

	 {
          "name": "Smear Type",
          "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/",
          "parent": "Blood Smear Images",
          "children": [
  	     {
              "name": "Thick & Thin Blood Smear",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick&Thin-CA.html",
              "parent": "Smear Type",
              "children": null
            },
            {
              "name": "Thick Blood Smear",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Smear Type",
              "children": null
            },
            {
              "name": "Thin Blood Smear",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thin-CA.html",
              "parent": "Smear Type",
              "children": null
            }
          ]
 },
	   {
          "name": "Stain Type",
          "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/",
          "parent": "Blood Smear Images",
          "children": [
  	     {
              "name": "Giemsa Stain",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick&Thin-CA.html",
              "parent": "Stain Type",
              "children": null
            },
            {
              "name": "Field Stain",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Stain Type",
              "children": null
            },
	    {
              "name": "Leishman Stain",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Stain Type",
              "children": null
            },
	    {
              "name": "May-Grünwald Giemsa Stain",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Stain Type",
              "children": null
            },
            {
              "name": "Modified Romanowsky Stain",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thin-CA.html",
              "parent": "Stain Type",
              "children": null
            }
          ]
       },

	 {
          "name": "Species",
          "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/",
          "parent": "Blood Smear Images",
          "children": [
  	     {
              "name": "Plasmodium falciparum",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick&Thin-CA.html",
              "parent": "Species",
              "children": null
            },
            {
              "name": "Plasmodium vivax",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Species",
              "children": null
            },
	    {
              "name": "Plasmodium malariae",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Species",
              "children": null
            },
            {
              "name": "Plasmodium ovale",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thin-CA.html",
              "parent": "Species",
              "children": null
            },
	    {
              "name": "Combined Species",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thin-CA.html",
              "parent": "Species",
              "children": null
            }
          ]
	 },

	      
        {
          "name": "Demography",
          "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/",
          "parent": "Blood Smear Images",
          "children": [
  	     {
              "name": "Africa",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick&Thin-CA.html",
              "parent": "Demography",
              "children": null
            },
            {
              "name": "Asia",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Demography",
              "children": null
            },
            {
              "name": "Europe",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thin-CA.html",
              "parent": "Demography",
              "children": null
            },
            {
              "name": "South America",
              "url": "https://itunuisewon.github.io/Malaria_Blood_Smear_Images/Controlled_Access/Thick-CA.html",
              "parent": "Demography",
              "children": null
            }
          ]
        }
      ]
    }
  ];

	
  // Color scale for node categories
  var categoryColorScale = d3.scale.category10();

  // Color scale for links
  var linkColorScale = d3.scale.category20();

  // ************** Generate the tree diagram	 *****************
  var margin = { top: 20, right: 120, bottom: 20, left: 120 },
    width = 960 - margin.right - margin.left,
    height = 500 - margin.top - margin.bottom;

  var i = 0,
    duration = 750,
    root;

  var tree = d3.layout.tree().size([height, width]);

  var diagonal = d3.svg.diagonal().projection(function (d) {
    return [d.y, d.x];
  });

  var svg = d3
    .select("#graph")
    .append("svg")
    .attr("width", width + margin.right + margin.left)
    .attr("height", height + margin.top + margin.bottom)
    .append("g")
    .attr("transform", "translate(" + margin.left + "," + margin.top + ")");

  root = treeData[0];
  root.x0 = height / 2;
  root.y0 = 0;

  update(root);

  d3.select(self.frameElement).style("height", "500px");

  function update(source) {
    // Compute the new tree layout.
    root = treeData[0];
    if (source.parent.name) {
      root = source.parent;
    }

    var nodes = tree.nodes(root).reverse(),
      links = tree.links(nodes);

    // Normalize for fixed-depth.
    nodes.forEach(function (d) {
      d.y = d.depth * 180;
    });

    // Update the nodes…
    var node = svg
      .selectAll("g.node")
      .data(nodes, function (d) {
        return d.id || (d.id = ++i);
      });

    // Enter any new nodes at the parent's previous position.
    var nodeEnter = node
      .enter()
      .append("g")
      .attr("class", "node")
      .attr("transform", function (d) {
        return "translate(" + source.y0 + "," + source.x0 + ")";
      })
      .on("click", click);

    nodeEnter
      .append("circle")
      .attr("r", 1e-6)
      .style("fill", function (d) {
        return categoryColorScale(d.name);
      }) // Color nodes based on their category
      .on("click", click);

    nodeEnter
      .append("a")
      .attr("xlink:href", function (d) {
        return d.url;
      })
      .append("text")
      .attr("x", function (d) {
        return d.children || d._children ? -13 : 13;
      })
      .attr("dy", ".35em")
      .attr("text-anchor", function (d) {
        return d.children || d._children ? "end" : "start";
      })
      .style("fill", function (d) {
        return categoryColorScale(d.name); // Color text based on category
      })
      .text(function (d) {
        return d.name;
      })
      .style("fill-opacity", 1e-6);

    // Transition nodes to their new position.
    var nodeUpdate = node
      .transition()
      .duration(duration)
      .attr("transform", function (d) {
        return "translate(" + d.y + "," + d.x + ")";
      });

    nodeUpdate
      .select("circle")
      .attr("r", 10)
      .style("fill", function (d) {
        return categoryColorScale(d.name);
      });

    nodeUpdate.select("text").style("fill-opacity", 1);

    // Transition exiting nodes to the parent's new position.
    var nodeExit = node
      .exit()
      .transition()
      .duration(duration)
      .attr("transform", function (d) {
        return "translate(" + source.y + "," + source.x + ")";
      })
      .remove();

    nodeExit.select("circle").attr("r", 1e-6);

    nodeExit.select("text").style("fill-opacity", 1e-6);

    // Update the links…
    var link = svg
      .selectAll("path.link")
      .data(links, function (d) {
        return d.target.id;
      });

    // Enter any new links at the parent's previous position.
    link
      .enter()
      .insert("path", "g")
      .attr("class", "link")
      .style("stroke", function (d) {
        // Assign colors to links based on the source node's category
        return linkColorScale(d.source.name);
      })
      .attr("d", function (d) {
        var o = { x: source.x0, y: source.y0 };
        return diagonal({ source: o, target: o });
      });

    // Transition links to their new position.
    link.transition().duration(duration).attr("d", diagonal);

    // Transition exiting nodes to the parent's new position.
    link
      .exit()
      .transition()
      .duration(duration)
      .attr("d", function (d) {
        var o = { x: source.x, y: source.y };
        return diagonal({ source: o, target: o });
      })
      .remove();

    // Stash the old positions for transition.
    nodes.forEach(function (d) {
      d.x0 = d.x;
      d.y0 = d.y;
    });
  }

  // Toggle children on click.
  function click(d) {
    if (d.children) {
      d._children = d.children;
      d.children = null;
    } else {
      d.children = d._children;
      d._children = null;
    }
    update(d);
  }
</script>


******
## All Datasets
*   [Aris et al., 2021 Image Dataset](All_Datasets/Aris_et_al.,_2021_Dataset.md)
*   [Davidson et al., 2021 Image Dataset](All_Datasets/Davidson_et_al.,_2021_Dataset.md)
*   [Khan et al., 2017 Image Dataset](All_Datasets/Khan_et_al.,_2017_Dataset.md)
*   [National Institute of Health _Plasmodium falciparum_ Image Dataset](All_Datasets/NIH_Pf_Dataset.md)
*   [Yoon et al., 2021 Image Dataset](All_Datasets/Yoon_et_al.,_2021_Dataset.md)
*   [Yu et al., 2023 Image Dataset](All_Datasets/Yu_et_al.,_2023_Dataset.md)
*   [Dave, 2018 Image Dataset](All_Datasets/Dave_2018_Dataset.md)
*   [Fong Amaris et al., 2022 Image Dataset](All_Datasets/Fong_Amaris_et_al.,_2022_Dataset.md)
*   [Koirala et al., 2022 Image Dataset](All_Datasets/Koirala_et_al.,_2022_Dataset.md)
*   [National Institute of Health _Plasmodium vivax_ Thick Blood Smear Image Dataset](All_Datasets/NIH_Pv_Dataset.md)
*   [Salamah et al., 2019 Image Dataset](All_Datasets/Salamah_et_al.,_2019_Dataset.md)
*   [de Souza Oliveira et al., 2022 Image Dataset](All_Datasets/de_Souza_Oliveira_et_al.,_2022_Dataset.md)
*   [Abdul-Nasir et al., 2015 Image Dataset](All_Datasets/Abdul-Nasir_et_al.,_2015_Dataset.md)
*   [Aladago et al., 2019 Image Dataset](All_Datasets/Aladago_et_al.,_2019.md)
*   [Arshad et al., 2022 Image Dataset](All_Datasets/Arshad_et_al.,_2022_Dataset.md)
*   [Cruz et al., 2016 Image Dataset](All_Datasets/Cruz_et_al.,_2016_Dataset.md)
*   [Dantas Oliveira et al., 2018 Image Dataset](All_Datasets/Dantas_Oliveira_et_al.,_2018_Dataset.md)
*   [Das et al., 2015 Image Dataset](All_Datasets/Das_et_al.,_2015_Dataset.md)
*   [Delas Peñas et al., 2018 Image Dataset](All_Datasets/Delas_Peñas_et_al.,_2018_Dataset.md)
*   [Delgado-Ortet et al., 2020 Image Dataset](All_Datasets/Delgado-Ortet_et_al.,_2020_Dataset.md)
*   [Devi et al., 2018 Image Dataset](All_Datasets/Devi_et_al.,_2018_Dataset.md)
*   [Diwan et al., 2014 Image Dataset](All_Datasets/Diwan_et_al.,_2014_Dataset.md)
*   [Fu et al., 2023 Image Dataset](All_Datasets/Fu_et_al.,_2023_Dataset.md)
*   [Hung et al., 2017 Image Dataset](All_Datasets/Hung_et_al.,_2017_Dataset.md)
*   [Kanafiah et al., 2022 Image Dataset](All_Datasets/Kanafiah_et_al.,_2022_Dataset.md)
*   [Loh et al., 2020 Image Dataset](All_Datasets/Loh_et_al.,_2020_Dataset.md)
*   [MP-IDB: The Malaria Parasite Image Database for Image Processing and Analysis](All_Datasets/MP-IDB.md)
*   [Maity et al., 2020 Image Dataset](All_Datasets/Maity_et_al.,_2020_Dataset.md)
*   [Mobile Thin Smear Malaria Parasites (mThinMPs) Image Database](All_Datasets/mThinMPs_Database.md)
*   [Molina et al., 2020 Image Dataset](All_Datasets/Molina_et_al.,_2020_Dataset.md)
*   [Mushabe et al., 2013 Image Dataset](All_Datasets/Mushabe_et_al.,_2013_Dataset.md)
*   [National Reference Center Dataset](All_Datasets/NRC_Dataset.md)
*   [Nugroho et al., 2014 Image Dataset](All_Datasets/Nugroho_et_al.,_2014_Dataset.md)
*   [Preedanan et al., 2016](All_Datasets/Preedanan_et_al.,_2016_Dataset.md)
*   [Rosnelly et al., 2017 Image Dataset](All_Datasets/Rosnelly_et_al.,_2017_Dataset.md)
*   [Sengar et al., 2022 Image Dataset](All_Datasets/Sengar_et_al.,_2022_Dataset.md)
*   [SmartMalariaNet](All_Datasets/SmartMalariaNet.md)
*   [Sunarko et al., 2017 Image Dataset](All_Datasets/Sunarko_et_al.,_2017_Dataset.md)
*   [Taiwan Images for Malaria Eradication (TIME) Image Dataset](All_Datasets/TIME_Dataset.md)
*   [The Broad Bioimage Benchmark Collection](All_Datasets/BBBC.md)
*   [Manescu et al., 2020 Image Dataset](All_Datasets/Manescu_et_al.,_2020_Dataset.md)
*   [Nakasi et al., 2021 Image Dataset](All_Datasets/Nakasi_et_al.,_2021_Dataset.md)


## **Usage**

To use any of the datasets in this repository, simply download the dataset from the corresponding link.


## **Contributions** 
If you are aware of any other malaria blood image datasets that are not included in this repository, please feel free to contribute to them by opening a pull request.



******
## **License**
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.