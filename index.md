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


+ [Smear Type](https://github.com/ItunuIsewon/Malaria_Blood_Smear_Images/blob/main/Smear_Type/README.md)
+ [Plasmodium falciparum](https://github.com/ItunuIsewon/Malaria_Blood_Smear_Images/blob/main/Parasite_Species/Plasmodium_falciparum.md)


## **Usage:**

To use any of the datasets in this repository, simply download the dataset from the corresponding link.


## **Contributions** 
If you are aware of any other malaria blood image datasets that are not included in this repository, please feel free to contribute to them by opening a pull request.


******
## **License**
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.