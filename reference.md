# Reference
## Api Latest
<details><summary><code>client.api.latest.<a href="src/fdr/api/latest/client.py">get_api_latest</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import uuid

from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.api.latest.get_api_latest(
    api_definition_id=uuid.UUID(
        "d5e9c84f-c2b2-4bf4-b4b0-7ffd7a9ffc32",
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**api_definition_id:** `ApiDefinitionId` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Api V1 Read
<details><summary><code>client.api.v_1.read.<a href="src/fdr/api/v_1/read/client.py">get_api</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import uuid

from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.api.v_1.read.get_api(
    api_definition_id=uuid.UUID(
        "d5e9c84f-c2b2-4bf4-b4b0-7ffd7a9ffc32",
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**api_definition_id:** `ApiDefinitionId` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Api V1 Register
<details><summary><code>client.api.v_1.register.<a href="src/fdr/api/v_1/register/client.py">register_api_definition</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.api.v_1.register.register_api_definition(
    org_id="orgId",
    api_id="apiId",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` 
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `ApiId` 
    
</dd>
</dl>

<dl>
<dd>

**definition:** `typing.Optional[ApiDefinition]` 
    
</dd>
</dl>

<dl>
<dd>

**definition_v_2:** `typing.Optional[ApiDefinition]` 
    
</dd>
</dl>

<dl>
<dd>

**sources:** `typing.Optional[typing.Dict[SourceId, Source]]` 
    
</dd>
</dl>

<dl>
<dd>

**dynamic_i_rs:** `typing.Optional[typing.Dict[str, DynamicIr]]` — A mapping of languages to dynamic IR.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Dashboard
<details><summary><code>client.dashboard.<a href="src/fdr/dashboard/client.py">get_docs_sites_for_org</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all docs sites that belong to a given organization
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.dashboard.get_docs_sites_for_org(
    org_id="orgId",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Docs V1 Read
<details><summary><code>client.docs.v_1.read.<a href="src/fdr/docs/v_1/read/client.py">get_docs_for_domain_legacy</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_1.read.get_docs_for_domain_legacy(
    domain="domain",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**domain:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_1.read.<a href="src/fdr/docs/v_1/read/client.py">get_docs_for_domain</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_1.read.get_docs_for_domain(
    domain="domain",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**domain:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Docs V1 Write
<details><summary><code>client.docs.v_1.write.<a href="src/fdr/docs/v_1/write/client.py">start_docs_register</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_1.write.start_docs_register(
    domain="domain",
    org_id="orgId",
    filepaths=["filepaths", "filepaths"],
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**domain:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**org_id:** `OrgId` 
    
</dd>
</dl>

<dl>
<dd>

**filepaths:** `typing.Sequence[FilePath]` — Relative filepath from docs folder.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_1.write.<a href="src/fdr/docs/v_1/write/client.py">finish_docs_register</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.docs.v_1.write import DocsConfig, DocsDefinition, PageContent

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_1.write.finish_docs_register(
    docs_registration_id="docsRegistrationId",
    docs_definition=DocsDefinition(
        pages={
            "pages": PageContent(
                markdown="markdown",
            )
        },
        config=DocsConfig(),
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**docs_registration_id:** `DocsRegistrationId` 
    
</dd>
</dl>

<dl>
<dd>

**docs_definition:** `DocsDefinition` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Docs V2 Read
<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">get_organization_for_url</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.get_organization_for_url(
    url="url",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">get_docs_url_metadata</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.get_docs_url_metadata(
    url="url",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">get_docs_for_url</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.get_docs_for_url(
    url="url",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">get_private_docs_for_url</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.get_private_docs_for_url(
    url="url",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">list_all_docs_urls</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a list of all public docs.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.list_all_docs_urls()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `typing.Optional[int]` 
    
</dd>
</dl>

<dl>
<dd>

**limit:** `typing.Optional[int]` 
    
</dd>
</dl>

<dl>
<dd>

**custom:** `typing.Optional[bool]` — If true, filters to only docs with a custom URL.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">get_docs_config_by_id</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Loads the Docs Config and any referenced APIs by ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.get_docs_config_by_id(
    docs_config_id="docsConfigId",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**docs_config_id:** `DocsConfigId` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.read.<a href="src/fdr/docs/v_2/read/client.py">prepopulate_fdr_read_s_3_bucket</a>()</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Prepopulates the FDR read S3 bucket with docs definitions
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.read.prepopulate_fdr_read_s_3_bucket()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Docs V2 Write
<details><summary><code>client.docs.v_2.write.<a href="src/fdr/docs/v_2/write/client.py">start_docs_register</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.write.start_docs_register(
    domain="domain",
    custom_domains=["customDomains", "customDomains"],
    org_id="orgId",
    api_id="apiId",
    filepaths=["filepaths", "filepaths"],
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**domain:** `str` — A `buildwithfern.com` url
    
</dd>
</dl>

<dl>
<dd>

**custom_domains:** `typing.Sequence[str]` 
    
</dd>
</dl>

<dl>
<dd>

**org_id:** `OrgId` 
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `ApiId` 
    
</dd>
</dl>

<dl>
<dd>

**filepaths:** `typing.Sequence[FilePath]` — Relative filepath from docs folder.
    
</dd>
</dl>

<dl>
<dd>

**auth_config:** `typing.Optional[AuthConfig]` 
    
</dd>
</dl>

<dl>
<dd>

**images:** `typing.Optional[typing.Sequence[ImageFilePath]]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.write.<a href="src/fdr/docs/v_2/write/client.py">start_docs_preview_register</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.write.start_docs_preview_register(
    org_id="orgId",
    filepaths=["filepaths", "filepaths"],
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` 
    
</dd>
</dl>

<dl>
<dd>

**filepaths:** `typing.Sequence[FilePath]` — Relative filepath from docs folder.
    
</dd>
</dl>

<dl>
<dd>

**base_path:** `typing.Optional[str]` 
    
</dd>
</dl>

<dl>
<dd>

**auth_config:** `typing.Optional[AuthConfig]` 
    
</dd>
</dl>

<dl>
<dd>

**images:** `typing.Optional[typing.Sequence[ImageFilePath]]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.write.<a href="src/fdr/docs/v_2/write/client.py">finish_docs_register</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.docs.v_1.write import DocsConfig, DocsDefinition, PageContent

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.write.finish_docs_register(
    docs_registration_id="docsRegistrationId",
    docs_definition=DocsDefinition(
        pages={
            "pages": PageContent(
                markdown="markdown",
            )
        },
        config=DocsConfig(),
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**docs_registration_id:** `DocsRegistrationId` 
    
</dd>
</dl>

<dl>
<dd>

**docs_definition:** `DocsDefinition` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.write.<a href="src/fdr/docs/v_2/write/client.py">transfer_ownership_of_domain</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.write.transfer_ownership_of_domain(
    domain="domain",
    to_org_id="toOrgId",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**domain:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**to_org_id:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.write.<a href="src/fdr/docs/v_2/write/client.py">set_is_archived</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.write.set_is_archived(
    url="url",
    is_archived=True,
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**is_archived:** `bool` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.docs.v_2.write.<a href="src/fdr/docs/v_2/write/client.py">set_docs_url_metadata</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs.v_2.write.set_docs_url_metadata(
    url="url",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**github_url:** `typing.Optional[Url]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Generators
<details><summary><code>client.generators.<a href="src/fdr/generators/client.py">upsert_generator</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update or create the specified generator.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.generators import GeneratorType_Sdk

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.upsert_generator(
    id="id",
    display_name="displayName",
    generator_type=GeneratorType_Sdk(),
    docker_image="dockerImage",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**id:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**display_name:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**generator_type:** `GeneratorType` 
    
</dd>
</dl>

<dl>
<dd>

**docker_image:** `str` — The name of the docker image to pull to run this generator.
    
</dd>
</dl>

<dl>
<dd>

**generator_language:** `typing.Optional[GeneratorLanguage]` 
    
</dd>
</dl>

<dl>
<dd>

**scripts:** `typing.Optional[GeneratorScripts]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.<a href="src/fdr/generators/client.py">get_generator_by_image</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the generator corresponding to the given docker image.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.get_generator_by_image(
    docker_image="dockerImage",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**docker_image:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.<a href="src/fdr/generators/client.py">get_generator</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the specified generator.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.get_generator(
    generator_id="generatorId",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**generator_id:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.<a href="src/fdr/generators/client.py">list_generators</a>()</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the all generators. This is currently not paginated since the list will be short, but there may in the future be need for pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.list_generators()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Diff
<details><summary><code>client.diff.<a href="src/fdr/diff/client.py">diff</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import uuid

from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.diff.diff(
    previous_api_definition_id=uuid.UUID(
        "d5e9c84f-c2b2-4bf4-b4b0-7ffd7a9ffc32",
    ),
    current_api_definition_id=uuid.UUID(
        "d5e9c84f-c2b2-4bf4-b4b0-7ffd7a9ffc32",
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**previous_api_definition_id:** `ApiDefinitionId` — The id of the previous version of the api definition
    
</dd>
</dl>

<dl>
<dd>

**current_api_definition_id:** `ApiDefinitionId` — The id of the current version of the api definition
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## DocsCache
<details><summary><code>client.docs_cache.<a href="src/fdr/docs_cache/client.py">invalidate</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.docs_cache.invalidate(
    url="url",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Generators Cli
<details><summary><code>client.generators.cli.<a href="src/fdr/generators/cli/client.py">get_latest_cli_release</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the latest CLI version that has not been yanked.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.cli.get_latest_cli_release()

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**release_types:** `typing.Optional[typing.Sequence[ReleaseType]]` — A filter for the release type, specifically if you'd like to get RC releases only, etc. Defaults to GA releases.
    
</dd>
</dl>

<dl>
<dd>

**ir_version:** `typing.Optional[int]` — The IR version that the CLI must respect.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.cli.<a href="src/fdr/generators/cli/client.py">get_changelog</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the changelog for the specified CLI upgrade. The response will be a map of the generator version to it's corresponding changelog.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.generators.commons import VersionRange_Inclusive

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.cli.get_changelog(
    from_version=VersionRange_Inclusive(value="fromVersion"),
    to_version=VersionRange_Inclusive(value="toVersion"),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**from_version:** `VersionRange` 
    
</dd>
</dl>

<dl>
<dd>

**to_version:** `VersionRange` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.cli.<a href="src/fdr/generators/cli/client.py">get_min_cli_for_ir</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the minimum CLI version that supports the given IR version. This does not include RCs.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.cli.get_min_cli_for_ir(
    ir_version=1,
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**ir_version:** `int` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.cli.<a href="src/fdr/generators/cli/client.py">upsert_cli_release</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update or create the specified CLI version.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.cli.upsert_cli_release(
    version="version",
    ir_version=1,
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**version:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**ir_version:** `int` — The major version of the IR that this CLI exposes.
    
</dd>
</dl>

<dl>
<dd>

**created_at:** `typing.Optional[dt.date]` 
    
</dd>
</dl>

<dl>
<dd>

**is_yanked:** `typing.Optional[Yank]` 
    
</dd>
</dl>

<dl>
<dd>

**changelog_entry:** `typing.Optional[typing.Sequence[ChangelogEntry]]` 
    
</dd>
</dl>

<dl>
<dd>

**tags:** `typing.Optional[typing.Sequence[str]]` — Tags to categorize the CLI release.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.cli.<a href="src/fdr/generators/cli/client.py">get_cli_release</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the specified CLI version.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.cli.get_cli_release(
    cli_version="cliVersion",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**cli_version:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.cli.<a href="src/fdr/generators/cli/client.py">list_cli_releases</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all CLI versions.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
response = client.generators.cli.list_cli_releases()
for item in response:
    yield item
# alternatively, you can paginate page-by-page
for page in response.iter_pages():
    yield page

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `typing.Optional[int]` — The page integer to retrieve. Defaults to 0.
    
</dd>
</dl>

<dl>
<dd>

**page_size:** `typing.Optional[int]` — The integer of items to retrieve per page. Defaults to 20.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Generators Versions
<details><summary><code>client.generators.versions.<a href="src/fdr/generators/versions/client.py">get_latest_generator_release</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the latest generator version that has not been yanked.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.versions.get_latest_generator_release(
    generator="generator",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**generator:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**cli_version:** `typing.Optional[str]` — The version of the CLI that is requesting the latest generator version. This is used to determine the latest IR version the generator must respect.
    
</dd>
</dl>

<dl>
<dd>

**ir_version:** `typing.Optional[int]` — The IR version that the generator must respect. If this is provided alongside `cliVersion`, `cliVersion` takes precedence.
    
</dd>
</dl>

<dl>
<dd>

**generator_major_version:** `typing.Optional[int]` — If specified, we will only return the latest version that is the same major version as provided. Useful while we do not support config migrations, etc.
    
</dd>
</dl>

<dl>
<dd>

**release_types:** `typing.Optional[typing.Sequence[ReleaseType]]` — A filter for the release type, specifically if you'd like to get RC releases only, etc. Defaults to GA releases.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.versions.<a href="src/fdr/generators/versions/client.py">get_changelog</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the changelog for the specified generator upgrade. The response will be a map of the generator version to it's corresponding changelog.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.generators.commons import VersionRange_Inclusive

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.versions.get_changelog(
    generator="generator",
    from_version=VersionRange_Inclusive(value="fromVersion"),
    to_version=VersionRange_Inclusive(value="toVersion"),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**generator:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**from_version:** `VersionRange` 
    
</dd>
</dl>

<dl>
<dd>

**to_version:** `VersionRange` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.versions.<a href="src/fdr/generators/versions/client.py">upsert_generator_release</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update or create the specified generator version.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.versions.upsert_generator_release(
    version="version",
    generator_id="generatorId",
    ir_version=1,
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**version:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**generator_id:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**ir_version:** `int` — The major version of the IR that this generator version consumes.
    
</dd>
</dl>

<dl>
<dd>

**created_at:** `typing.Optional[dt.date]` 
    
</dd>
</dl>

<dl>
<dd>

**is_yanked:** `typing.Optional[Yank]` 
    
</dd>
</dl>

<dl>
<dd>

**changelog_entry:** `typing.Optional[typing.Sequence[ChangelogEntry]]` 
    
</dd>
</dl>

<dl>
<dd>

**migration:** `typing.Optional[str]` — The TypeScript file for the migration to run when upgrading to this version. Ideally this would be typed as a file, but we don't support file upload in the express generator.
    
</dd>
</dl>

<dl>
<dd>

**custom_config_schema:** `typing.Optional[str]` — The JSON schema (stringified) for the custom config that this generator version supports.
    
</dd>
</dl>

<dl>
<dd>

**tags:** `typing.Optional[typing.Sequence[str]]` — Tags to categorize the Generator release.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.versions.<a href="src/fdr/generators/versions/client.py">get_generator_release</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the specified generator version.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.generators.versions.get_generator_release(
    generator="generator",
    version="version",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**generator:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**version:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.generators.versions.<a href="src/fdr/generators/versions/client.py">list_generator_releases</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all generator versions for the specified generator.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
response = client.generators.versions.list_generator_releases(
    generator="generator",
)
for item in response:
    yield item
# alternatively, you can paginate page-by-page
for page in response.iter_pages():
    yield page

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**generator:** `GeneratorId` 
    
</dd>
</dl>

<dl>
<dd>

**page:** `typing.Optional[int]` — The page integer to retrieve. Defaults to 0.
    
</dd>
</dl>

<dl>
<dd>

**page_size:** `typing.Optional[int]` — The integer of items to retrieve per page. Defaults to 20.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Git
<details><summary><code>client.git.<a href="src/fdr/git/client.py">get_repository</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a repository by its name (mirroring the Github API, this is the main get request).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.git.get_repository(
    repository_owner="repositoryOwner",
    repository_name="repositoryName",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**repository_owner:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">list_repositories</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all repositories.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
response = client.git.list_repositories()
for item in response:
    yield item
# alternatively, you can paginate page-by-page
for page in response.iter_pages():
    yield page

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `typing.Optional[int]` — The page number to retrieve. Defaults to 0.
    
</dd>
</dl>

<dl>
<dd>

**page_size:** `typing.Optional[int]` — The number of items to retrieve per page. Defaults to 20.
    
</dd>
</dl>

<dl>
<dd>

**organization_id:** `typing.Optional[OrgId]` — The Fern organization ID to filter repositories by.
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `typing.Optional[str]` — The name of the repository to filter pull requests by (ex: full-platform).
    
</dd>
</dl>

<dl>
<dd>

**repository_owner:** `typing.Optional[str]` — The organization name of the repository owner to filter pull requests by (ex: fern-api).
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">upsert_repository</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update or create the specified repository.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import datetime

from fdr import FdrClient
from fdr.git import CheckRun, FernRepository_Sdk, RepositoryId_Github

client = FdrClient(
    token="YOUR_TOKEN",
)
client.git.upsert_repository(
    request=FernRepository_Sdk(
        sdk_language="sdkLanguage",
        id=RepositoryId_Github(
            id="id",
        ),
        name="name",
        owner="owner",
        full_name="fullName",
        url="url",
        repository_owner_organization_id="repositoryOwnerOrganizationId",
        default_branch_checks=[
            CheckRun(
                check_id="checkId",
                repository_owner="repositoryOwner",
                repository_name="repositoryName",
                ref="ref",
                name="name",
                status="status",
                conclusion="conclusion",
                check_run_url="checkRunUrl",
                created_at=datetime.datetime.fromisoformat(
                    "2024-01-15 09:30:00+00:00",
                ),
                raw_check_run={"key": "value"},
            ),
            CheckRun(
                check_id="checkId",
                repository_owner="repositoryOwner",
                repository_name="repositoryName",
                ref="ref",
                name="name",
                status="status",
                conclusion="conclusion",
                check_run_url="checkRunUrl",
                created_at=datetime.datetime.fromisoformat(
                    "2024-01-15 09:30:00+00:00",
                ),
                raw_check_run={"key": "value"},
            ),
        ],
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernRepository` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">delete_repository</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete specified repository.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.git.delete_repository(
    repository_owner="repositoryOwner",
    repository_name="repositoryName",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**repository_owner:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">get_pull_request</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a pull request by its ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.git.get_pull_request(
    repository_owner="repositoryOwner",
    repository_name="repositoryName",
    pull_request_number=1,
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**repository_owner:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**pull_request_number:** `int` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">list_pull_requests</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get all pull requests.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
response = client.git.list_pull_requests()
for item in response:
    yield item
# alternatively, you can paginate page-by-page
for page in response.iter_pages():
    yield page

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `typing.Optional[int]` — The page number to retrieve. Defaults to 0.
    
</dd>
</dl>

<dl>
<dd>

**page_size:** `typing.Optional[int]` — The number of items to retrieve per page. Defaults to 20.
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `typing.Optional[str]` — The name of the repository to filter pull requests by (ex: full-platform).
    
</dd>
</dl>

<dl>
<dd>

**repository_owner:** `typing.Optional[str]` — The organization name of the repository owner to filter pull requests by (ex: fern-api).
    
</dd>
</dl>

<dl>
<dd>

**organization_id:** `typing.Optional[OrgId]` — The Fern organization ID to filter repositories by.
    
</dd>
</dl>

<dl>
<dd>

**state:** `typing.Optional[typing.Sequence[PullRequestState]]` — The status(es) of the pull request to filter by.
    
</dd>
</dl>

<dl>
<dd>

**author:** `typing.Optional[typing.Sequence[str]]` — The login (github username) of the author(s) to filter by.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">upsert_pull_request</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update or create the specified pull request.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import datetime

from fdr import FdrClient
from fdr.git import CheckRun, PullRequestReviewer_User

client = FdrClient(
    token="YOUR_TOKEN",
)
client.git.upsert_pull_request(
    pull_request_number=1,
    repository_name="repositoryName",
    repository_owner="repositoryOwner",
    reviewers=[
        PullRequestReviewer_User(
            username="username",
        ),
        PullRequestReviewer_User(
            username="username",
        ),
    ],
    title="title",
    url="url",
    checks=[
        CheckRun(
            check_id="checkId",
            repository_owner="repositoryOwner",
            repository_name="repositoryName",
            ref="ref",
            name="name",
            status="status",
            conclusion="conclusion",
            check_run_url="checkRunUrl",
            created_at=datetime.datetime.fromisoformat(
                "2024-01-15 09:30:00+00:00",
            ),
            raw_check_run={"key": "value"},
        ),
        CheckRun(
            check_id="checkId",
            repository_owner="repositoryOwner",
            repository_name="repositoryName",
            ref="ref",
            name="name",
            status="status",
            conclusion="conclusion",
            check_run_url="checkRunUrl",
            created_at=datetime.datetime.fromisoformat(
                "2024-01-15 09:30:00+00:00",
            ),
            raw_check_run={"key": "value"},
        ),
    ],
    state="open",
    created_at=datetime.datetime.fromisoformat(
        "2024-01-15 09:30:00+00:00",
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**pull_request_number:** `int` 
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**repository_owner:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**reviewers:** `typing.Sequence[PullRequestReviewer]` 
    
</dd>
</dl>

<dl>
<dd>

**title:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**url:** `Url` 
    
</dd>
</dl>

<dl>
<dd>

**checks:** `typing.Sequence[CheckRun]` 
    
</dd>
</dl>

<dl>
<dd>

**state:** `PullRequestState` 
    
</dd>
</dl>

<dl>
<dd>

**created_at:** `dt.datetime` 
    
</dd>
</dl>

<dl>
<dd>

**author:** `typing.Optional[GithubUser]` 
    
</dd>
</dl>

<dl>
<dd>

**updated_at:** `typing.Optional[dt.datetime]` 
    
</dd>
</dl>

<dl>
<dd>

**merged_at:** `typing.Optional[dt.datetime]` 
    
</dd>
</dl>

<dl>
<dd>

**closed_at:** `typing.Optional[dt.datetime]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.git.<a href="src/fdr/git/client.py">delete_pull_request</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete specified pull request.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.git.delete_pull_request(
    repository_owner="repositoryOwner",
    repository_name="repositoryName",
    pull_request_number=1,
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**repository_owner:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**repository_name:** `str` 
    
</dd>
</dl>

<dl>
<dd>

**pull_request_number:** `int` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Sdks Versions
<details><summary><code>client.sdks.versions.<a href="src/fdr/sdks/versions/client.py">compute_semantic_version</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Computes a semantic version for the SDK to be relesed on.
The endpoint tries to find existing versions by looking up against 
registries and github repositories. If none are found an error is thrown. 
If a version is found, a new semantic version is returned.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.sdks.versions.compute_semantic_version(
    package="package",
    language="Go",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**package:** `str` — The name of the package (e.g. `@org/sdk` or `com.org:org-java`)
    
</dd>
</dl>

<dl>
<dd>

**language:** `Language` 
    
</dd>
</dl>

<dl>
<dd>

**github_repository:** `typing.Optional[str]` 

The name of the GitHub repository (e.g. `owner/repo`). 
The repositories latest release will be queried to find the existing 
package version.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SnippetsFactory
<details><summary><code>client.snippets_factory.<a href="src/fdr/snippets_factory/client.py">create_snippets_for_sdk</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Store endpoint snippets for a particular SDK.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.commons import EndpointIdentifier
from fdr.snippets import TypeScriptSdk
from fdr.snippets_factory import (
    SdkSnippetsCreate_Typescript,
    SingleTypescriptSnippetCreate,
    TypeScriptSnippetCode,
)

client = FdrClient(
    token="YOUR_TOKEN",
)
client.snippets_factory.create_snippets_for_sdk(
    org_id="orgId",
    api_id="apiId",
    snippets=SdkSnippetsCreate_Typescript(
        sdk=TypeScriptSdk(
            package="package",
            version="version",
        ),
        snippets=[
            SingleTypescriptSnippetCreate(
                snippet=TypeScriptSnippetCode(
                    client="client",
                ),
                endpoint=EndpointIdentifier(
                    path="path",
                    method="GET",
                ),
            ),
            SingleTypescriptSnippetCreate(
                snippet=TypeScriptSnippetCode(
                    client="client",
                ),
                endpoint=EndpointIdentifier(
                    path="path",
                    method="GET",
                ),
            ),
        ],
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` — The organization to create snippets for.
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `ApiId` — The API name.
    
</dd>
</dl>

<dl>
<dd>

**snippets:** `SdkSnippetsCreate` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Snippets
<details><summary><code>client.snippets.<a href="src/fdr/snippets/client.py">get</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get snippet by endpoint method and path
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.commons import EndpointIdentifier

client = FdrClient(
    token="YOUR_TOKEN",
)
client.snippets.get(
    endpoint=EndpointIdentifier(
        method="GET",
        path="/v1/search",
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**endpoint:** `EndpointIdentifier` 
    
</dd>
</dl>

<dl>
<dd>

**org_id:** `typing.Optional[OrgId]` 

If the same API is defined across multiple organization,
you must specify an organization ID.
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `typing.Optional[ApiId]` — If you have more than one API, you must specify its ID.
    
</dd>
</dl>

<dl>
<dd>

**sdks:** `typing.Optional[typing.Sequence[SdkRequest]]` 

The SDKs for which to load snippets. If unspecified,
snippets for the latest published SDKs will be returned.
    
</dd>
</dl>

<dl>
<dd>

**example_identifier:** `typing.Optional[str]` — The identifier of the example to fetch the snippet for, this is ignored if a payload is passed in.
    
</dd>
</dl>

<dl>
<dd>

**payload:** `typing.Optional[CustomSnippetPayload]` 

The JSON payload to be used as the input for the code snippet. This should just be thought of as the
request body you'd be sending to the endpoint as a cURL. If not specified then the default payload will be used.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.snippets.<a href="src/fdr/snippets/client.py">load</a>(...)</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.snippets import SdkRequest_Python

client = FdrClient(
    token="YOUR_TOKEN",
)
client.snippets.load(
    page=1,
    org_id="vellum",
    api_id="vellum-ai",
    sdks=[
        SdkRequest_Python(
            package="vellum-ai",
        )
    ],
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**page:** `typing.Optional[int]` 
    
</dd>
</dl>

<dl>
<dd>

**org_id:** `typing.Optional[OrgId]` 

If the same API is defined across multiple organization,
you must specify an organization ID.
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `typing.Optional[ApiId]` — If you have more than one API, you must specify its ID.
    
</dd>
</dl>

<dl>
<dd>

**sdks:** `typing.Optional[typing.Sequence[SdkRequest]]` 

The SDKs for which to load snippets. If unspecified,
snippets for the latest published SDKs will be returned.
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Templates
<details><summary><code>client.templates.<a href="src/fdr/templates/client.py">register</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Store endpoint snippet for a particular SDK.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import uuid

from fdr import FdrClient
from fdr.commons import EndpointIdentifier
from fdr.snippets import Sdk_Typescript
from fdr.templates import (
    SnippetRegistryEntry,
    Template_Generic,
    VersionedSnippetTemplate_V1,
)

client = FdrClient(
    token="YOUR_TOKEN",
)
client.templates.register(
    org_id="orgId",
    api_id="apiId",
    api_definition_id=uuid.UUID(
        "d5e9c84f-c2b2-4bf4-b4b0-7ffd7a9ffc32",
    ),
    snippet=SnippetRegistryEntry(
        sdk=Sdk_Typescript(
            package="package",
            version="version",
        ),
        endpoint_id=EndpointIdentifier(
            path="path",
            method="GET",
        ),
        snippet_template=VersionedSnippetTemplate_V1(
            client_instantiation="clientInstantiation",
            function_invocation=Template_Generic(
                is_optional=True,
                template_string="templateString",
            ),
        ),
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` — The organization to create snippets for.
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `ApiId` — The API name.
    
</dd>
</dl>

<dl>
<dd>

**api_definition_id:** `ApiDefinitionId` 
    
</dd>
</dl>

<dl>
<dd>

**snippet:** `SnippetRegistryEntry` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.templates.<a href="src/fdr/templates/client.py">register_batch</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Store endpoint snippets for a particular SDK.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
import uuid

from fdr import FdrClient
from fdr.commons import EndpointIdentifier
from fdr.snippets import Sdk_Typescript
from fdr.templates import (
    SnippetRegistryEntry,
    Template_Generic,
    VersionedSnippetTemplate_V1,
)

client = FdrClient(
    token="YOUR_TOKEN",
)
client.templates.register_batch(
    org_id="orgId",
    api_id="apiId",
    api_definition_id=uuid.UUID(
        "d5e9c84f-c2b2-4bf4-b4b0-7ffd7a9ffc32",
    ),
    snippets=[
        SnippetRegistryEntry(
            sdk=Sdk_Typescript(
                package="package",
                version="version",
            ),
            endpoint_id=EndpointIdentifier(
                path="path",
                method="GET",
            ),
            snippet_template=VersionedSnippetTemplate_V1(
                client_instantiation="clientInstantiation",
                function_invocation=Template_Generic(
                    is_optional=True,
                    template_string="templateString",
                ),
            ),
        ),
        SnippetRegistryEntry(
            sdk=Sdk_Typescript(
                package="package",
                version="version",
            ),
            endpoint_id=EndpointIdentifier(
                path="path",
                method="GET",
            ),
            snippet_template=VersionedSnippetTemplate_V1(
                client_instantiation="clientInstantiation",
                function_invocation=Template_Generic(
                    is_optional=True,
                    template_string="templateString",
                ),
            ),
        ),
    ],
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` — The organization to create snippets for.
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `ApiId` — The API name.
    
</dd>
</dl>

<dl>
<dd>

**api_definition_id:** `ApiDefinitionId` 
    
</dd>
</dl>

<dl>
<dd>

**snippets:** `typing.Sequence[SnippetRegistryEntry]` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.templates.<a href="src/fdr/templates/client.py">get</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the endpoint's snippet template for a particular SDK.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient
from fdr.commons import EndpointIdentifier
from fdr.snippets import SdkRequest_Typescript

client = FdrClient(
    token="YOUR_TOKEN",
)
client.templates.get(
    org_id="orgId",
    api_id="apiId",
    sdk=SdkRequest_Typescript(
        package="package",
    ),
    endpoint_id=EndpointIdentifier(
        path="path",
        method="GET",
    ),
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` — The organization to create snippets for.
    
</dd>
</dl>

<dl>
<dd>

**api_id:** `ApiId` — The API name.
    
</dd>
</dl>

<dl>
<dd>

**sdk:** `SdkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**endpoint_id:** `EndpointIdentifier` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Tokens
<details><summary><code>client.tokens.<a href="src/fdr/tokens/client.py">generate</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate a token
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.tokens.generate(
    org_id="orgId",
    scope="scope",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` — The organization to generate a token for.
    
</dd>
</dl>

<dl>
<dd>

**scope:** `str` 

The scope of the token. Valid scopes include: 
  - admin 
  - sdk:read:{package_name}
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.tokens.<a href="src/fdr/tokens/client.py">revoke</a>(...)</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Revoke a token
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```python
from fdr import FdrClient

client = FdrClient(
    token="YOUR_TOKEN",
)
client.tokens.revoke(
    org_id="orgId",
    token_id="tokenId",
)

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**org_id:** `OrgId` — The organization to create snippets for.
    
</dd>
</dl>

<dl>
<dd>

**token_id:** `TokenId` 
    
</dd>
</dl>

<dl>
<dd>

**request_options:** `typing.Optional[RequestOptions]` — Request-specific configuration.
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

