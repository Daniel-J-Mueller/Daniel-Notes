Models have to store context within the model weights during generation.

The burden of this process can be lessened if the context is offloaded to a referencable notes section.

Then, the model will allow this temporary context storage to dissipate, enabling better considerations of other things.