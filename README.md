# pyMODCS

showdown.extension('targetlink', function() {
  return [{
    type: 'html',
    regex: /(<a [^>]+?)(>.*<\/a>)/g,
    replace: '$1 target="_blank"$2'
  }];
});

<a href="http://reslnxinglab01.research.chop.edu/public/panz/" target="_blank">link text</a>


