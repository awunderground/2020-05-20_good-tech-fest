# Iterating Branded Fact Sheets and Web Pages With R Markdown

[Slides](https://awunderground.github.io/2020-05-20_good-tech-fest/slides)

Whether it’s a mayor trying to tackle the opioid epidemic in California or a nationwide foundation trying to better understand how to serve varied communities, decision makers want information that will help them solve their problems. To inform policymakers at the state and local levels, the Urban Institute built a tool for iterating branded fact sheets and websites with R Markdown. With this tool, researchers can create a parameterized template that generates a PDF, html website, or plain text R Markdown document and then iterate that template over a data set with information at the state or county level. The template can contain text, images, tables, and figures and all elements can update based on the data passed to the parameters. This makes it super easy for researchers to distill exhaustive reports about many communities into fact sheets or websites with the relevant information for the individual communities where decisions are made. 

We will demonstrate how we used this tool in conjunction with R packages like urbnthemes, which makes ggplot2 visualizations meet the branding standard of the Urban Institute and urbnmapr, which can be used to quickly create state and county maps in R. Join us as we discuss the design and applications of the tool and demonstrate how it can be used by any organization to iterate branded and parameterized reports across geography, time, or any meaningful subset of data. 

## Related content

[HTML example](https://www.urban.org/policy-centers/cross-center-initiatives/state-and-local-finance-initiative/projects/state-fiscal-briefs)

[PDF example](https://www.urban.org/policy-centers/income-and-benefits-policy-center/projects/expanding-eitc-workers-without-resident-children)

[Iterated fact sheets with R Markdown](https://medium.com/@urban_institute/iterated-fact-sheets-with-r-markdown-d685eb4eafce) 

[Iterated PDFs with R Markdown](https://medium.com/@urban_institute/iterated-pdfs-with-r-markdown-144e2a6d6a1a) 
