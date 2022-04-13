# Photo Gallery

Build a [Pinterest style](https://www.pinterest.com/cabiclothing/handbags/)
web page that displays information from the following API endpoint.

    http://xoosha.com/ws/1/test.php?offset=20

The endpoint accepts an `offset` url parameter and  returns a list of items
sorted by the `crawled_time` field.

## Requirements

### Basics

- The page should work and look good on popular desktop browsers.
- The page should allow users view **all items** behind the endpoint. That is, not just one page, but all items accessible by changing the `offset` parameter. The standard interface solution for this is pagination (displaying items in pages).
- The page should be available online via a URL. We do not deploy and host your
    code.

### Exrta Score

- **Infinite-scroll:** Let users view more items by just scrolling. <br />
To see an example, visit [here](https://www.pinterest.com/cabiclothing/handbags/) and scroll to the end of the page. Notice how more items are loaded automatically.
- **Mobile Web:** Make sure your page works and looks good on popular mobile browsers.
- **Client-side Search:** Add a serach feature that filters items based on data in the `description` field of each item. Search only needs to work on the items loaded so far.

### Delivery
- Please message us in [our Discord](https://discord.gg/PVPSj3CJ) with the URL.
