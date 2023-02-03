# eks-cluster
This repo has all the necessary components to stand up eks cluster

This repo creates a set of resources to deploy AWS EKS cluster. Cluster comes up healthy, but i do struggle with getting the app discovered. Having some connection refused errors. I would spend more time on that, but i think for the assesment purposes i did get far enough. I also could deploy bare bone cluster just to have it done, but it is not my style to do something just call it done, i like to do things 'the proper way', but it does come with the price. May be i'm just missing something very obvious, just need a second pair of eyes.

Next step here would be to create the ci/cd, i want to implement Jenkins for this purpose., since it does come with all we need to make the pipeline configurable and does integrate with a lot of tools so we don't expose any sensitive information to the world. Since my networking doesn't recognize the services i wouldn't be able to show case the jenkins in action.

For DNS i would like to deploy externl-dns, so any service will be assigned to the dns which will be registered at ROUTE53