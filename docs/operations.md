# Operations #

## PutObject ##

* [PutObject on AWS](http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectPUT.html)

### Params ###

<table>
  <thead>
    <tr>
      <th width="20%">Param Name</th>
      <th width="10%">Required</th>
      <th width="10%">Type</th>
      <th width="60%">Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>BucketName</td>
      <td>required</td>
      <td>special</td>
      <td></td>
    </tr>
    <tr>
      <td>ObjectName</td>
      <td>required</td>
      <td>special</td>
      <td></td>
    </tr>
    <tr>
      <td>Range</td>
      <td>optional</td>
      <td>header</td>
      <td></td>
    </tr>
    <tr>
      <td>IfModifiedSince</td>
      <td>optional</td>
      <td>header</td>
      <td></td>
    </tr>
    <tr>
      <td>IfUnmodifiedSince</td>
      <td>optional</td>
      <td>header</td>
      <td></td>
    </tr>
    <tr>
      <td>IfMatch</td>
      <td>optional</td>
      <td>header</td>
      <td></td>
    </tr>
    <tr>
      <td>IfNoneMatch</td>
      <td>optional</td>
      <td>header</td>
      <td></td>
    </tr>
    <tr>
      <td>ResponseContentType</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
    <tr>
      <td>ResponseContentLanguage</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
    <tr>
      <td>ResponseExpires</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
    <tr>
      <td>ResponseCacheControl</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
    <tr>
      <td>ResponseContentDisposition</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
    <tr>
      <td>ResponseContentEncoding</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
    <tr>
      <td>VersionId</td>
      <td>optional</td>
      <td>param</td>
      <td></td>
    </tr>
  </tbody>
</table>

## GetObject ##

* [GetObject on AWS](http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGETacl.html)

(Ends)
