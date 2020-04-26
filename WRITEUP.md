# Project Write-Up

You can use this document as a template for providing your project write-up. However, if you
have a different format you prefer, feel free to use it as long as you answer all required
questions.

## Explaining Custom Layers

The process behind converting custom layers involves...

Some of the potential reasons for handling custom layers are...

## Comparing Model Performance

My method(s) to compare models before and after conversion to Intermediate Representations
were...

The difference between model accuracy pre- and post-conversion was...

The size of the model pre- and post-conversion was...

The inference time of the model pre- and post-conversion was...

## Assess Model Use Cases

Some of the potential use cases of the people counter app are listed in:

[4 Business Models for a People Counter App at the Edge.](https://medium.com/@santiagomartnez_69416/4-business-models-for-a-people-counter-app-at-the-edge-4c48b9f8e0c0)



## Assess Effects on End User Needs

Lighting, model accuracy, and camera focal length/image size have different effects on a
deployed edge model. The potential effects of each of these are as follows...

- Lighting depends on the application and environment. Examples. 
	Solutions, expand dataset, train on B&W. Preprocess image.

- Model Accuracy is also dependant on the application. Optimize your truth matrix 
	(False positives & False Negatives), get asessory from a statician.
	Personally, images very close to the treshold I would send them to the server
	for human classification.
	Continuous retraining.
	Sustaiin a random process for verification. 

- Image Size, afects performance. This is better adderesed from the begining. 
	Important to consider budget as well, as scope and scale of the project.
	This is one of the first to focus as the model is dependant on this.
	Affects speed as well. Little flexibility to pivot with end user from.

  
- Focal Length.
	Unless working in conjunction with a photography knowledgable expert.
	Worry about this until production, ideally this would be the parameter that allow
	for different locations to get the same view. 
	REgularize images based on plausible locations.
  

## Model Research

[This heading is only required if a suitable model was not found after trying out at least three
different models. However, you may also use this heading to detail how you converted 
a successful model.]

In investigating potential people counter models, I tried each of the following three models:

- Model 1: [Name]
  - [Model Source]
  - I converted the model to an Intermediate Representation with the following arguments...
  - The model was insufficient for the app because...
  - I tried to improve the model for the app by...
  
- Model 2: [Name]
  - [Model Source]
  - I converted the model to an Intermediate Representation with the following arguments...
  - The model was insufficient for the app because...
  - I tried to improve the model for the app by...

- Model 3: [Name]
  - [Model Source]
  - I converted the model to an Intermediate Representation with the following arguments...
  - The model was insufficient for the app because...
  - I tried to improve the model for the app by...
