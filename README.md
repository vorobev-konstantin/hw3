1. Для установки nginx-ingress запустить скрипт install-nginx-ingress.sh в директории nginx-ingress
2. Для запуска выполнить

   kubectl create namespace app  
   kubectl config set-context --current --namespace=app  
   kubectl apply -f .  
   
3. Для проверки работоспособности проверить что отрабатывает сл. url -ы

   http://arch.homework/health  
   http://arch.homework/otusapp/aeugene/health
   
4. Для удаления kubectl delete ns app
