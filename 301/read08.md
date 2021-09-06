### What does REST stand for?
REST or RESTful API design (Representational State Transfer) is designed to take advantage of existing protocols. While REST can be used over nearly any protocol, it usually takes advantage of HTTP when used for Web APIs. This means that developers do not need to install libraries or additional software in order to take advantage of a REST API design. REST API Design was defined by Dr. Roy Fielding in his 2000 doctorate dissertation. It is notable for its incredible layer of flexibility. Since data is not tied to methods and resources, REST has the ability to handle multiple types of calls, return different data formats and even change structurally with the correct implementation of hypermedia.
### What is an identifer of a resource?
The essence of the merge comes down to answering the question “When is a node in one graph the same node as a node in another graph?” In RDF, this issue is resolved through the use of Uniform Resource Identifiers (URIs). 
example:
***For the purposes of explaining modeling on the Semantic Web, the detailed URIs behind the qnames are not important, so for the most part, we will omit these bindings from now on. In many examples, we will take this notion of abbreviation one step further; in the cases when we use a single namespace throughout one example, we will assume there is a default namespace declaration that allows us to refer to URIs simply with a symbolic name preceded by a colon (:), such as :Shakespeare, :JamesDean, :Researcher.***

### What are the most common HTTP verbs?
HTTP defines a set of request methods to indicate the desired action to be performed for a given resource. Although they can also be nouns, these request methods are sometimes referred to as HTTP verbs.
### What status code does a successful GET request return?
201 Created
The request has succeeded and a new resource has been created as a result. This is typically the response sent after POST requests, or some PUT requests. 
### What status code does an unsuccessful GET request return? 
A 404 status code does not indicate whether the resource is temporarily or permanently missing. But if a resource is permanently removed, a 410 (Gone) should be used instead of a 404 status. 


### What status code does a successful POST request return?
The action performed by the POST method might not result in a resource that can be identified by a URI. In this case, either 200 (OK) or 204 (No Content) is the appropriate response status, depending on whether or not the response includes an entity that describes the result.

### What status code does a successful DELETE request return?
Responses. If a DELETE method is successfully applied, there are several response status codes possible: A 202 ( Accepted ) status code if the action will likely succeed but has not yet been enacted. A 204 ( No Content ) status code if the action has been enacted and no further information is to be supplied.

![1](https://www.programmableweb.com/sites/default/files/Five-Best-Practices-for-Building-an-Effective-API-Marketplace-Figure-1-Key-components-of-an-API-Marketplace.png)