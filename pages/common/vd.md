# vd

> VisiData — a terminal utility for exploring and arranging tabular data
> More information: <http://visidata.org>

- Explore a CSV file, an XLSX file and a JSON file:

`vd {{file1.csv}} {{file2.xlsx}} {{file3.json}}`

- scrape HTML table data from a webpage:

`vd {{https://en.wikipedia.org/wiki/List_of_largest_cities}}`

- Convert a CSV file to a JSON file:

`vd -b {{input.csv}} -o {{output.json}}`

- See a visual diff of two sheets with the same structure:

`vd --diff {{file1.csv}} {{file2.csv}}`

- Replay a previously saved set of commands:

`vd -p {{file.vd}}`
