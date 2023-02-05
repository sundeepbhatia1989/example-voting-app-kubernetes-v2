# example-voting-app-kubernetes-v2
#This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) from docker-examples(https://github.com/dockersamples)


Hi Friends,
My name is Sundeep.

Connect to cluster using kubectl
#az aks get-credentials --resource-group myResourceGroup --name myAKSCluster
az aks get-credentials --resource-group votingapp-resourcegroup --name example-voting-app

kubectl get nodes


git init
git config --global user.email "sundeepbhatia1989@gmail.com"
git config --global user.name "sundeepbhatia198
git remote add origin git@github.com:sundeepbhatia1989/example-voting-app-kubernetes-v2.git
git commit -m "first commit"
git add .
git push -u origin main

If you are facing this error message during pushing code to git.
-----------------
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.
--------------------
This is because you are not add publick key in git repository.
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Please follow https://kodekloud.com/community/t/demo-deploying-voting-app-on-kubernetes/98366
