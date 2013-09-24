# CollegeDesis Scripts

This repo collects fun scripts that student organizations can embed into their own websites to awesomeness.

## Radio

CollegeDesis has collected over South Asian DJs from all around the country. We'll get the latest and greatest music to show off the music. All you have to do is add a couple lines to your website!

### Usage

Add the following lines to any html page, preferrably inside the `<head>` tag.

```html

<script type='text/javascript' src='scripts.collegedesis.com/radio.js'></script>
<script type='text/javascript'>
  $.collegeDesisRadio({
    channel: 'fusion',
    randomize: true,
    autoPlay: false
  });
</script>
```

You can also change the values of  `randomize` and `autoPlay`. Possible values for `channel` are `bhangra` and `fusion`. We hope to release `acappella`, `pop`, and `hiphop` channels soon!
