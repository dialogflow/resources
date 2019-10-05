# Dialogflow libraries and samples
Dialogflow's APIs allow you to take action on your own systems based on conversational input, embed your conversational interface into your app or website, and dynamically change your agent's behavior. Dialogflow APIs center around three primary use cases:

![](https://raw.githubusercontent.com/dialogflow/resources/master/images/overview.png)

* **Fulfillment**: take action on your own systems based on conversational input. You can do things like querying a database or API to provide info to your users with any integration (Actions on Google, Slack, etc.)
* **Detect Intent API**: Embed your conversational interface built with Dialogflow into your app, website or device. Call this API with a user's query to get back how your DIalogflow agent's response
* **Agent API**: Dynamically change your agent's behavior by editing your agent's intents, entities and contexts. Do anything you can through Dialogflow console programmatically with Dialogflow's agent APIs.

## Fulfillment
Fulfillment is code that's deployed as a webhook that lets your Dialogflow agent call business logic on an intent-by-intent basis. During a conversation, fulfillment allows you to use the information extracted by Dialogflow's natural language processing to generate dynamic responses or trigger actions on your back-end.

Most Dialogflow agents make use of fulfillment to do things like: generate dynamic responses based on information looked up from a database, place orders based on products a customer has asked for, implement the rules and winning conditions for a game.

### Library

| **Platform** | **Package Manager** | **Quick Start** | **Getting Started** |
|--------------|---------------------|-----------------|---------------------|
| [Node.js](https://github.com/dialogflow/dialogflow-fulfillment-nodejs) | [npm](https://npmjs.org/package/dialogflow-fulfillment) | [Quick Start Guide](https://github.com/dialogflow/dialogflow-fulfillment-nodejs#quick-start) | [Getting Started Guide](/docs/getting-started/building-your-first-agent) |

Note: For all other platforms please see API reference for a [webhook request](https://dialogflow.com/docs/reference/api-v2/rest/v2beta1/WebhookRequest) and [response](https://dialogflow.com/docs/reference/api-v2/rest/v2beta1/WebhookResponse).

### Samples
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
    <th></th>
  </tr>
  <tr class="alt">
    <td colspan="3"><b>Node.js</b></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-actions-library-nodejs" target="_blank">Actions on Google</a></td>
    <td>Sample demonstrating how to use both the Dialogflow fulfillment library and the Actions on Google client library together.</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https://oneclickgithub.appspot.com/dialogflow/fulfillment-actions-library-nodejs&agentName=ActionsLibrary" class="gc-analytics-event" data-category="dialogflow" data-label="actions-library-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png"></a>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-bike-shop-nodejs" target="_blank">Bike Shop</a></td>
    <td>Dive into making a agent for a small business like this appointment scheudling bike shop</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https%3A%2F%2Fstorage.googleapis.com%2Fdialogflow-oneclick%2Fbike-shop-agent.zip&agentName=BikeShopSample" class="gc-analytics-event" data-category="dialogflow" data-label="bike-shop-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png"></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-faq-nodejs" target="_blank">FAQ</a></td>
    <td>Description: Sample desmonstrating how to use Knowledge Connectors, the Telephony Gateway and Actions on Google together.</td>
    <td></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-firestore-nodejs" target="_blank">Firestore</a></td>
    <td>Sample demonstrating how to connect a Dialogflow agent to Firebase's Firestore database.</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https://oneclickgithub.appspot.com/dialogflow/fulfillment-firestore-nodejs&agentName=FirestoreSample" class="gc-analytics-event" data-category="dialogflow" data-label="firestore-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png"></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/agent-human-handoff-nodejs" target="_blank">Human-agent Handoff</a></td>
    <td>This sample consists of a simple API.AI agent, a node.js server and a web interface that together demonstrate an approach for handing text-based conversations from an API.AI agent to a human operator."</td>
    <td></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-importer-nodejs" target="_blank">Import</a></td>
    <td>A simple sample showing how to use Dialogflow's Importer for Alexa Skills to import a Alexa Skill to Dialogflow and deploy it to the Google Assistant."</td>
    <td></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-multi-locale-nodejs" target="_blank">Multi locale/language</a></td>
    <td>Create and fulfill a multilingual and multilocale agent with this French and English speaking sample</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https://oneclickgithub.appspot.com/dialogflow/fulfillment-multi-locale-nodejs&agentName=MultilocaleSample" target="_blank" class="gc-analytics-event" data-category="dialogflow" data-label="multi-language-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png"></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-webhook-nodejs" target="_blank">Quick Start</a></td>
    <td>Get started quickly with fulfillment with this basic code</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https%3A%2F%2Fstorage.googleapis.com%2Fdialogflow-oneclick%2Fquickstart-agent.zip&agentName=QuickStartSample" class="gc-analytics-event" data-category="dialogflow" data-label="quick-start-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png"></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-regex-nodejs" target="_blank">Regular expression entity validation.</a></td>
    <td>Sample demonstrating how to validate a entity with a regular expression in fulfillment.</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https://oneclickgithub.appspot.com/dialogflow/fulfillment-regex-nodejs&agentName=RegexSample" class="gc-analytics-event" data-category="dialogflow" data-label="regex-one-click" target="_blank"> <img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png"></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-temperature-converter-nodejs" target="_blank">Temperature Converter Trivia</a></td>
    <td>Learn how intent, entities, contexts and rich responses work with this sample that converts temperatures with trivia along the way</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https%3A%2F%2Fstorage.googleapis.com%2Fdialogflow-oneclick%2Ftemperature-converter-agent.zip&agentName=TemperatureConverterSample" class="gc-analytics-event" data-category="dialogflow" data-label="temp-converter-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png" alt="Temperature Converter Trivia" title="Temperature Converter Trivia"></a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-weather-nodejs" target="_blank">Weather</a></td>
    <td>Make a API call from fulfillment to give user's relevant information like the weather</td>
    <td><a href="https://console.dialogflow.com/api-client/oneclick?templateUrl=https%3A%2F%2Fstorage.googleapis.com%2Fdialogflow-oneclick%2Fweather-agent.zip&agentName=WeatherSample" class="gc-analytics-event" data-category="dialogflow" data-label="weather-one-click" target="_blank"><img src="https://raw.githubusercontent.com/dialogflow/resources/master/images/deploy.png" alt="Weather" title="Weather"></a></td>
  </tr>
  <tr class="alt">
    <td colspan="3"><b>Python/Flask</b></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-translate-python" target="_blank">Translate</a></td>
    <td>Get information from the user in the form of Dialogflow parameters and make an API call with the data to translate user's speech from one language to another</td>
    <td></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-weather-python" target="_blank">Weather</a></td>
    <td>Make a API call from fulfillment to give user's relevant information like the weather</td>
    <td></td>
  </tr>
  <tr class="alt">
    <td colspan="3"><b>JSON</b></td>
  </tr>
  <tr>
    <td><a href="https://github.com/dialogflow/fulfillment-webhook-json" target="_blank">Webhook Request & Response</a></td>
    <td>This sample shows Dialogflow's fulfillment webhook JSON requests and responses for v1 & v2 agents, including Actions on Google-specific requests & resposnes"</td>
    <td></td>
  </tr>
</table>

### Actions on Google
Actions on Google has created a library and samples specifically for use with Dialogflow and Actions on Google together.  These tools and samples do *not* work with any other Dialogflow integrations.
#### Library
If you are only interested in building Dialogflow fulfillment for the Google Assistant and don't plan on using other integrations, you should use the [Actions on Google fulfillment library](https://github.com/actions-on-google/actions-on-google-nodejs) which supports all Actions on Google features.
#### Samples
For fulfillment samples specific to Google Assistant please see <a href="https://developers.google.com/actions/samples/#dialogflow" target="_blank">Actions on Google's Dialogflow sample page</a>

## Detect Intent and Agent APIs
Dialogflow's detect intent API is a great way to integrate your Dialogflow agent into your website or app. The detect intent API enables you to query your agent with a user's request (audio or text) and receive your agent's response to the user's request.

The agent API allows you to dynamically change the behavior of your Dialogflow agent by allowing you to create, read, update and delete intents, entities and contexts. Both the detect intent and agent APIs can be accessed through Dialogflow's REST API or the client libraries available for Node.js, Python, Java, Go, Ruby, C#, and PHP listed below:

### API V2
#### Libraries
| **Platform** | **Package Manager** | **Installation** | **Include/Import** |
|--------------|---------------------|------------------|--------------------|
| [Node.js](https://github.com/dialogflow/dialogflow-nodejs-client-v2) | [NPM](https://www.npmjs.com/package/dialogflow) | `npm install dialogflow` | `const dialogflow = require('dialogflow');` |
| [Python](https://github.com/dialogflow/dialogflow-python-client-v2) | [PyPI](https://pypi.python.org/pypi/dialogflow) | `pip install dialogflow` | `import dialogflow` |
| [Java](https://github.com/GoogleCloudPlatform/google-cloud-java/tree/master/google-cloud-clients/google-cloud-dialogflow) | [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-dialogflow) | [See Quickstart](https://github.com/GoogleCloudPlatform/google-cloud-java/tree/master/google-cloud-clients/google-cloud-dialogflow#quickstart) | `import com.google.cloud.dialogflow.V2.*;` |
| [Go](https://github.com/GoogleCloudPlatform/google-cloud-go/tree/master/dialogflow/apiv2) | [go get](https://godoc.org/cloud.google.com/go/dialogflow/apiv2) | `go get cloud.google.com/go/dialogflow/apiv2` | `import "cloud.google.com/go/dialogflow/apiv2"` |
| [Ruby](https://github.com/GoogleCloudPlatform/google-cloud-ruby/tree/master/google-cloud-dialogflow) | [Gem](https://rubygems.org/gems/google-cloud-dialogflow) | `gem install api-ai-ruby` | `ApiAiRuby::Client.new(...)` |
| [C#](https://github.com/GoogleCloudPlatform/google-cloud-dotnet/tree/master/apis/Google.Cloud.Dialogflow.V2) | [Nuget](https://www.nuget.org/packages/Google.Cloud.Dialogflow.V2) | `nuget install Google.Cloud.Dialogflow.V2` | `using Google.Cloud.Dialogflow.V2;` |
| [PHP](https://github.com/GoogleCloudPlatform/google-cloud-php-dialogflow) | [Packagist](https://packagist.org/packages/google/cloud-dialogflow) | `composer require google/cloud-dialogflow` | `use Google\Cloud\Dialogflow\V2\AgentsClient;` |

#### Samples
| **Platform** | **Samples** |
|--------------|----------|
| Node.js | https://github.com/googleapis/nodejs-dialogflow/tree/master/samples |
| Python | https://github.com/googleapis/dialogflow-python-client-v2/tree/master/samples |
| Java | https://github.com/GoogleCloudPlatform/java-docs-samples/tree/master/dialogflow/cloud-client |
| Go | https://github.com/GoogleCloudPlatform/google-cloud-go/tree/master/dialogflow/apiv2 |
| C# | https://github.com/googleapis/google-cloud-dotnet/tree/master/apis/Google.Cloud.Dialogflow.V2/Google.Cloud.Dialogflow.V2.Snippets |
| PHP | https://github.com/GoogleCloudPlatform/php-docs-samples/tree/master/dialogflow |
| Ruby | https://github.com/GoogleCloudPlatform/ruby-docs-samples/tree/master/dialogflow |

### API V2 <sup>BETA</sup>

Dialogflow's V2beta1 offers new features that are not yet available on the generally available and may make some backwards incompatible changes.

#### Libraries
| **Platform** | **Package Manager** | **Installation** | **Include/Import** |
|--------------|---------------------|------------------|--------------------|
| [Node.js](https://github.com/dialogflow/dialogflow-nodejs-client-v2) | [npm](https://www.npmjs.com/package/dialogflow) | `npm install dialogflow` | `const dialogflow = require('dialogflow').V2beta1;` |
| [Python](https://github.com/dialogflow/dialogflow-python-client-v2/tree/master/dialogflow_v2beta1) | [PyPi](https://pypi.python.org/pypi/dialogflow) | `pip install dialogflow` | `import dialogflow_V2beta1` |
| [Java](https://github.com/GoogleCloudPlatform/google-cloud-java/tree/master/google-api-grpc/grpc-google-cloud-dialogflow-v2beta1) | [Maven](https://mvnrepository.com/artifact/com.google.cloud/google-cloud-dialogflow) | [See Quickstart](https://github.com/GoogleCloudPlatform/google-cloud-java/tree/master/google-cloud-dialogflow#quickstart) | `import com.google.cloud.dialogflow.V2beta1.*;` |

#### Samples
| **Platform** | **Samples** |
|--------------|----------|
| Python | https://github.com/googleapis/dialogflow-python-client-v2/tree/master/samples |
| Java | https://github.com/GoogleCloudPlatform/java-docs-samples/tree/master/dialogflow/cloud-client |
| Node.js | https://github.com/googleapis/nodejs-dialogflow/tree/master/samples |

### API V1 (Legacy)
#### Libraries
Dialogflow's legacy V1 SDKs can be found below. When starting a new project, use Dialogflow V2 and V2 SDKs listed above.

| **Platform** | **Docs** |
|--------------|----------|
| [Android SDK](https://github.com/dialogflow/dialogflow-android-client) | [Android SDK Docs](https://github.com/dialogflow/dialogflow-android-client#android-sdk-for-dialogflow) |
| [Botkit SDK](https://github.com/dialogflow/dialogflow-botkit-client) | [Botkit SDK Docs](https://github.com/dialogflow/dialogflow-botkit-client#api-ai-botkit) |
| [C++](https://github.com/dialogflow/dialogflow-cpp-client) | [C++ Docs](https://github.com/dialogflow/dialogflow-cpp-client#c-library-for-apiai) |
| [Cordova SDK](https://github.com/dialogflow/dialogflow-cordova-client) | [Cordova SDK Docs](https://github.com/dialogflow/dialogflow-cordova-client#api-ai-cordova) |
| [HTML + JS Example](https://gist.github.com/Gugic/cfc008599fa9a82eeba4127648009132) ||
| [iOS SDK](https://github.com/dialogflow/dialogflow-apple-client) | [iOS SDK Docs](https://github.com/dialogflow/dialogflow-apple-client/blob/master/README.md) |
| [Java SDK](https://github.com/dialogflow/dialogflow-java-client) | [Java SDK Docs](https://github.com/dialogflow/dialogflow-java-client#java-sdk-for-apiai) |
| [JavaScript SDK](https://github.com/dialogflow/dialogflow-javascript-client) | [JavaScript SDK Docs](https://github.com/dialogflow/dialogflow-javascript-client#installation) |
| [.NET (WP8, W10)](https://github.com/dialogflow/dialogflow-dotnet-client) | [.NET SDK Docs](https://github.com/dialogflow/dialogflow-dotnet-client#apiai-net-library) |
| [Node.js SDK](https://github.com/dialogflow/dialogflow-nodejs-client) | [Node.js SDK Docs](https://github.com/dialogflow/dialogflow-nodejs-client#nodejs-sdk-for-apiai) |
| [Python SDK](https://github.com/dialogflow/dialogflow-python-client) | [Python SDK Docs](https://github.com/dialogflow/dialogflow-python-client#apiai-python-sdk-for-apiai-httpapiai_) |
| [Ruby SDK](https://github.com/dialogflow/dialogflow-ruby-client) | [Ruby SDK Docs](https://github.com/dialogflow/dialogflow-ruby-client#the-apiai-ruby-gem) |
| [Unity SDK](https://github.com/dialogflow/dialogflow-unity-client) | [Unity SDK Docs](https://github.com/dialogflow/dialogflow-unity-client#apiai-unity-plugin) |
| [Xamarin SDK](https://github.com/dialogflow/dialogflow-xamarin-client) | [Xamarin SDK Docs](https://github.com/dialogflow/dialogflow-xamarin-client#api-ai-xamarin) |
