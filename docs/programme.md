<!-- # Programme -->

<!-- The last version of the programme can be found here: -->

<!-- <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSX2gWNptsTDTVwK52gmw3upZAdg9R8DJZiXxeSVKxIl3Syn8CjqC2_WRi61K2s_1AHQXYAqf5I0_3u/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="100%" height="100%" style="border:0; position:absolute; top:0; left:0; bottom:0; right:0;" allowfullscreen></iframe> -->


<!-- <iframe src="https://docs.google.com/document/d/1WTD64wFU8kiLUhPD-0amli0EFL8TRWiHVmEkwB8xsgw/pub?embedded=true" width=600 height=450 style="border:0; position:absolute; top:0; left:0; bottom:0; right:0;" allowfullscreen></iframe> -->

<!-- <iframe src="https://docs.google.com/document/d/1WTD64wFU8kiLUhPD-0amli0EFL8TRWiHVmEkwB8xsgw/pub?embedded=true" width="100%" height="100%" style="border:0;" allowfullscreen></iframe> -->


<!-- <style>
  body, html {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
    overflow: hidden /* ; Hide overflow to prevent double scrollbars */
  }

  .iframe-container {
    position: relative;
    width: 100%;
    height: 100vh; /* Full viewport height */
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .iframe-container iframe {
    width: 100%;
    height: 100%;
    border: none; /* Remove borders to avoid double scrollbars */
 }
</style>

<div class="iframe-container">
  <iframe src="https://docs.google.com/document/d/1WTD64wFU8kiLUhPD-0amli0EFL8TRWiHVmEkwB8xsgw/pub?embedded=true" allowfullscreen></iframe>
</div> -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Embedded Document</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow: hidden; /* Prevent scrolling on the body */
      /* font-family: Arial, sans-serif; Set a clean, default font */
    }

    .iframe-container {
      position: absolute;
      width: 100%;
      height: 100vh; /* Full viewport height */
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f9f9f9; /* Light background for better contrast */
    }

    .iframe-wrapper {
      width: 100%;
      height: 100%;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Subtle shadow for depth */
    }

    .iframe-wrapper iframe {
      width: 100%;
      height: 100%;
      border: none; /* Remove borders to avoid double scrollbars */
      border-radius: inherit; /* Inherit parent's border radius */
    }
  </style>
</head>
<body>

<div class="iframe-container">
  <div class="iframe-wrapper">
    <iframe src="https://docs.google.com/document/d/1WTD64wFU8kiLUhPD-0amli0EFL8TRWiHVmEkwB8xsgw/pub?embedded=true" allowfullscreen title="Embedded Document"></iframe>
  </div>
</div>

</body>
</html>

