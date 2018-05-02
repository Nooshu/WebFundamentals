project_path: /web/tools/_project.yaml
book_path: /web/tools/_book.yaml
description: TODO

{# wf_updated_on: 2018-05-02 #}
{# wf_published_on: 2018-05-01 #}
{# wf_blink_components: N/A #}

# Migration Guide: Lighthouse 2 to 3 {: .page-title }

This guide is for Lighthouse users who:

* Run Lighthouse from Node or the command line.
* Rrely on the JSON output of Lighthouse.

If these do not apply to you, then your workflow for running Lighthouse is mostly the same.
See [Announcing Lighthouse 3.0](/web/updates/2018/05/lighthouse3) for an overview of new
features and changes.

## Overview {: #overview }

To migrate from Lighthouse version 2 to 3, you may need to make changes regarding how you:

* [Configure Lighthouse to run](#config).
* [Consume Lighthouse's JSON output](#output).

## Configuration changes {: #config }

## JSON output changes {: #output }

The table below lists all of the changes that you need to make regarding how you consume
the JSON output of Lighthouse.

* If a row has a value in both **v2** and **v3** columns, it means
  that you should replace any reference to the v2 property in your code with the v3-equivalent.
* If a row does not have a value in the **v3** column, 
* Note that items such as <var>ID</var> represent placeholder text.

<table>
  <tr>
    <th>v2 Property</th>
    <th>v3-Equivalent</th>
    <th>Notes</th>
  </tr>
  <tr>
    <td><code>initialUrl</code></td>
    <td><code>requestedUrl</code></td>
    <td></td>
  </tr>
  <tr>
    <td><code>reportGroups</code></td>
    <td></td>
    <td>Removed. Use TODO instead.</td>
  </tr>
  <tr>
    <td><code>timing</code></td>
    <td></td>
    <td>Removed. Use TODO instead.</td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.name</code></td>
    <td><code>audits.<var>ID</var>.id</code></td>
    <td>
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.description</code></td>
    <td><code>audits.<var>ID</var>.title</code></td>
    <td>
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.helpText</code></td>
    <td><code>audits.<var>ID</var>.description</code></td>
    <td>
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.displayValue</code></td>
    <td></td>
    <td>
      Removed. Use TODO instead.
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.notApplicable</code></td>
    <td></td>
    <td>
      Removed. Use TODO instead.
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.informative</code></td>
    <td></td>
    <td>
      Removed. Use TODO instead.
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.manual</code></td>
    <td></td>
    <td>
      Removed. Use TODO instead.
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.rawValue</code></td>
    <td></td>
    <td>
      Removed. Use TODO instead.
    </td>
  </tr>
  <tr>
    <td><code>audits.<var>ID</var>.extendedInfo</code></td>
    <td></td>
    <td>
      Removed. Use TODO instead.
    </td>
  </tr>
</table>
