# Vuetify with vite speed issue
run `pnpm install`
run `pnpm dev`
go to localhost:300
go to the network tab and see a lot of pending sass/scss requests
Once done, click on the Go to test link
And once again see a lot of pending requests
When you repeat this, the speed is excelent
When you cut the server, and rerun pnpm dev, the speed is slow again for the first time.


Keep in mind that this is a really really small project, just the starter of vuetify with 3 simple components on the test page.
My pc the loading time is about 4s here. On my real project, it's about 20s and after every new page with 1 simple new component again.
This test project only has 1 page.


You could add some more pages and components to see the difference in speed. For exmaple adding VDataTable adds makes it go up to 11 seconds
