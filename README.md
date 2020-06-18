# How We Investigated Banned Items on Amazon.com
This repository contains data related to our story, "[Amazon’s Enforcement Failures Leave Open a Seedy Back Door to Banned Goods—Some Sold and Shipped by Amazon Itself](https://themarkup.org/banned-bounty/2020/06/18/amazons-enforcement-failures-leave-open-a-back-door)".

Our methodology is described in "[How We Investigated Banned Items on Amazon.com](https://themarkup.org/banned-bounty/2020/06/18/how-we-investigated-banned-items-on-amazon-com)".

The data for our findings can be found in the data folder.

## Data

This folder contains the data we created in reporting our story.

Our findings consist of a spreadsheet of the prohibited product listings we found, and a collection of timestamped screenshots for the listing pages. Links to the individual screenshots are in the spreadsheet. The screenshots of all of the prohibited product listings we found are included in their entirety so that you can see the listings as they appeared to us in our reporting. We have also included a second, short spreadsheet of banned items that did not meet one aspect of our criteria but we mention in the story and shared with Amazon.

You can grab the full collection of screenshots from this repository: [https://github.com/the-markup/investigation-amazon-banned-items-screenshots](https://github.com/the-markup/investigation-amazon-banned-items-screenshots/)


**amazon-banned-items-findings.csv**
A list of the items we found on Amazon.com in the course of our investigation. 

**amazon-banned-items-additional-items.csv**
Additional banned items mentioned in story. 

## Data Dictionary:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: left;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>restricted_product_category</strong></td>
      <td>The Restricted Products category that the prohibited product falls under.</td>
    </tr>
    <tr>
      <td><strong>prohibited_policy_text</strong></td>
      <td>The specific text of the prohibition from the Restricted Products policy page. Bulleted list items include the text at the top of the list.</td>
    </tr>
    <tr>
      <td><strong>policy_page</strong></td>
      <td>A link to a timestamped screenshot of the Restricted Products policy page that covers this prohibition.</td>
    </tr>
    <tr>
      <td><strong>item_type</strong></td>
      <td>Description of the item.</td>
    </tr>
     <tr>
      <td><strong>asin</strong></td>
      <td>The Amazon Standard Identification Number (ASIN) is an alphanumeric unique identifier for products in Amazon's catalog.</td>
    </tr>
    <tr>
      <td><strong>screenshot</strong></td>
      <td>A link to a full page screenshot of the product listing.</td>
    </tr>
   <tr>
      <td><strong>listing_url</strong></td>
      <td>The URL of the product listing that we found.</td>
    </tr>
  </tbody>
</table>

Main findings link: [Formatted](https://github.com/the-markup/investigation-amazon-banned-items/blob/master/data/amazon-banned-items-findings.csv) | [Raw](https://raw.githubusercontent.com/the-markup/investigation-amazon-banned-items/master/data/amazon-banned-items-findings.csv?token=AADIYQZYOK5H56RIINPDSNK66P46Q)

Additional items link: [Formatted](https://github.com/the-markup/investigation-amazon-banned-items/blob/master/data/amazon-banned-items-additional-items.csv) | [Raw](https://raw.githubusercontent.com/the-markup/investigation-amazon-banned-items/master/data/amazon-banned-items-additional-items.csv?token=AADIYQYQQD3O6TR7DPR6UYS66P5A6)


## Licensing
Copyright 2020, The Markup News Inc.

This license applies solely to the source code. This license does not apply to any of the photographs and/or screenshots provided and/or linked to in this GitHub, including but not limited to any and all images, text, trademarks, service marks and logos contained therein (collectively, the “**Photographs**”). Any and all Photographs are provided solely as evidence of The Markup’s research and The Markup has no claim in and to the Photographs and/or any and all intellectual property contained therein. 

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
