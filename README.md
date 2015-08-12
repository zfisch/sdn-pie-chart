# SDN Pie Chart

## Specially Designated Nationals List (SDN) by Country

The data for this project is collected from the [Office of Foreign Asset Control website](http://www.treasury.gov/ofac/downloads/sdn.xml).

Each SDN is analyzed for its address, nationality, and citizenship, and prescribed associations with countries accordingly. Each SDN may only be associated with a given country one time, though it may be associated with multiple countries. Country association percentages are determined by dividing the number of a single country's associations with SDN's by the number of all country associations with SDN's.

### To View the Chart
1. Clone the repo to your computer and navigate to the root directory.
2. Start a local static development server (I recommend [httpster](http://simbco.github.io/httpster/)).
  1. If you want to use httpster: `npm install -g httpster`
  2. When you're inside the project directory, run `httpster`.
  3. Navigate your web browser to `localhost:3333`.