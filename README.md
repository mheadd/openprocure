# Open Procure
## Open Source list of Public Agencies Procurement Thresholds

See it live at http://openprocure.us/

The static pages are in the gh-pages branch and the Middleman template is
in the master branch.

### To add procurement thresholds

[Edit `data/procurement.yaml` directly on GitHub](https://github.com/munirent/openprocure/edit/master/data/procurement.yaml).  Once you save the edited `procurement.yaml` file, it will automatically deploy to the live website.  It takes about 1 min and you need to refresh your browser, but it is really that simple.  No further action required.  Or you can always fork the repository and submit a pull request.  

### When adding a PDF as a link
Make sure you append the page number at the end.  If I wanted to add a link to **page 2** of [this PDF](http://www.publishers.org.uk/_resources/assets/attachment/full/0/2091.pdf), I would add a `#page=2` at the end of the URL. e.g. `http://www.publishers.org.uk/_resources/assets/attachment/full/0/2091.pdf#page=2`.

### To install

1. Clone repository
2. Install ruby and bundler for your system
3. `bundle install`

### To run in development

`middleman`

### To deploy changes

`rake deploy`

## License

To the extent possible under law, MuniRent has waived all copyright and
related or neighboring rights to Open Procure. This work is published
from: United States.

[See LICENSE.txt](LICENSE.txt) for more details.

