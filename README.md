# Azure Cognitive Services - Speech to Text Batch Transcription

Microsoft's [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) are a set of machine learning models for problems such as object recognition, sentiment analysis, entity extraction, and speech to text. 

This demo uses the [Speech API's](https://azure.microsoft.com/en-us/services/cognitive-services/directory/speech/) Speech to Text Batch Transcription service to transcribe audio from an Azure Blob Storage Container

## Prerequisites

- Data must be uploaded into an Azure Blob Storage Container
- Audio files must be in either WAV or MP3 format (with PCM Codec) or OGG (OPUS Codec), with a bitrate of 16-bit and a sample rate of either 8 or 16 kHz, in either mono or stero.
- A [Cognitive Services Speech Subscription](https://ms.portal.azure.com/#blade/Microsoft_Azure_Marketplace/GalleryFeaturedMenuItemBlade/selectedMenuItemId/home/searchQuery/speech/resetMenuId/) will be required, using a **standard** tier subscription

Further details are available from the [documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/batch-transcription#prerequisites)

A [Swagger](https://uksouth.cris.ai/docs/v2.0/swagger) is available for API testing and documentation (see "Custom Speech Transcriptions" section). **Note you may need to change the region URL from uksouth to where you've provisioned the Speech API in the following section.**
