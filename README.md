# Bookmarker-Application-using-Javascript

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5307e6c8363e455babcdea1e2678bb1a)](https://www.codacy.com/manual/viraldevpb/Bookmarker-Application-using-Javascript?utm_source=github.com&utm_medium=referral&utm_content=viraldevpb/Bookmarker-Application-using-Javascript&utm_campaign=Badge_Grade)

This is an Bookmarker Application created using Javascript and this repository helps you create a bookmark of popular Websites in your own Browser..

## Technology used : HTML,CSS and Javascript

## Usage

Just Clone this repositry in your PC or Laptop or Download this project in your PC

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Site Bookmarker</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/style.css" rel="stylesheet">
  </head>

  <body onload="fetchBookmarks()">

    <div class="container">
      <div class="header clearfix">
        <nav>

        </nav>
        <center><h3 class="text-muted">Bookmarker</h3></center>
      </div>

      <div class="jumbotron">
        <h2>Bookmark Your Favorite Sites</h2>
        <form id="myForm">
          <div class="form-group">
            <label>Site Name</label>
            <input type="text" class="form-control" id="siteName" placeholder="Website Name">
          </div>
          <div class="form-group">
            <label>Site URL</label>
            <input type="text" class="form-control" id="siteUrl" placeholder="Website URL">
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>

      <div class="row marketing">
        <div class="col-lg-12">
          <div id="bookmarksResults"></div>
        </div>
      </div>

      <footer class="footer">
        <p>&copy; 2020 Bookmarker, Inc.</p>
      </footer>

    </div> <!-- /container -->

    <script
    src="https://code.jquery.com/jquery-3.1.1.js"
    integrity="sha256-16cdPddA6VdVInumRGo6IbivbERE8p7CQR3HzTBuELA="
    crossorigin="anonymous"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/main.js"></script>
  </body>
</html>
```

For detailed explanation, visite [How To](https://code.visualstudio.com/docs/editor/github)

```bash
$ git@github.com:viraldevpb/Bookmarker-Application-using-Javascript.git
```

## Questions or Suggestions

Feel free to create issues [here](https://github.com/viraldevpb/Bookmarker-Application-using-Javascript/issues)

## [Try it](https://github.com/viraldevpb/Bookmarker-Application-using-Javascript)

## [Follow me on Instagram for daily coding posts](https://www.instagram.com/theshycoder/)
