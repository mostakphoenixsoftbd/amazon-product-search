# Amazon Product Search
<img width="60%" src="https://cosmicjs.imgix.net/26b41d70-5f9a-11e7-b120-9f6bc26aeb8f-amazon-product-search.jpg" />

Search Amazon's product catalouge and add products with afiliate links to your [Cosmic JS](https://cosmicjs.com) Bucket.  [Read the blog article](https://cosmicjs.com/blog/building-and-publishing-a-cosmic-js-extension-using-bitbucket-pipelines) to learn how it was built.
### Getting Started
```
git clone https://github.com/cosmicjs/amazon-product-search
cd amazon-product-search
yarn
yarn start
```
http://localhost:3000?bucket_slug=your-bucket-slug&read_key=bucket-read-key&write_key=bucket-write-key.

### Installing the Extension
To add this Extension to your Bucket simply install it from Your Bucket > Extensions > Browse Extensions and find this Extension.

Or you can upload the build as a zip file to your Bucket:
1. Run the build command which creates a zip of the build folder
```
yarn build
```
2. Go to Your Bucket > Extensions > Upload Extension and drop the zip file
## Documentation
To build your own Cosmic JS Extension, [read the Cosmic JS Extensions documentation](https://cosmicjs.com/docs/extensions).
