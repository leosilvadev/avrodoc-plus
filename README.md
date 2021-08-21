# avrodoc-plus

## DEPRECATION NOTICE - USE mobimeo/avrodoc-plus

This library is not maintained anymore, use https://github.com/mobimeo/avrodoc-plus instead.

<hr/>

avrodoc-plus is a documentation tool for [Apache Avro](http://avro.apache.org/) schemas.  
This project originates from [https://github.com/ept/avrodoc](https://github.com/ept/avrodoc) and [https://github.com/ckatzorke/avrodoc-plus](https://github.com/ckatzorke/avrodoc.plus), which are great, but received no further updates.

## Usage

```bash
npm install --global @leosilvadev/avrodoc-plus | yarn add global @leosilvadev/avrodoc-plus
avrodoc-plus -i source -o out.html
```

### Options

* -i *sourcefolder*  
   Pass in a source folder that will recursively parsed and crawled for avsc files
* -o *outputfile*  
  The file where the generated doc should be written to
* -s *external stylesheet less file*  
  Your own less file, used to override specific style of your generated page

### Enhancements

- support for input folders
- support of schema/type search (search by namespace and/or schema/type)
