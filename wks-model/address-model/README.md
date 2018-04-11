## Steps from [WKS Documentation](https://console.bluemix.net/docs/services/watson-knowledge-studio/index.html#wks_overview_full) to Upload WKS Artifacts from another WKS workspace

### Order of Upload Operations
**Type System** - `JSON`<br>

To upload a type system, open the **Assets & Tools** > **Entity Types** page and click **Upload** to upload the JSON file that you downloaded.

**Dictionaries** - `ZIP` or `CSV`

*Note:* DO NOT RUN THE DICTIONARY PRE-ANNOTATOR, OR ANY OTHER PRE-ANNOTATOR

To upload dictionaries, open the Dictionaries tab and either add a CSV file that you downloaded or upload the ZIP file if multiple files.

To make sure the dictionary is not a preview only dictionary go to **Manage Dictionaries** > Click **Create Dictionary**. Label the dictionaries, then click **Upload** to import the CSV.

Once dictionary is uploaded make sure to map each dictionary to an Entity Type in the drop menu.

**Documents** - `ZIP`

To upload documents, open the Document Sets tab in the new workspace, click **Upload Document Sets** and select the corpus ZIP file that you downloaded. Specify whether you want the uploaded documents to include or exclude the ground truth annotations before you click **Upload**. Only annotations that were promoted to ground truth before the documents were downloaded will be uploaded.
