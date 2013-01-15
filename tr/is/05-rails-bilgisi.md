# Rails Bilgisi

Bu bölümde sizden bir kütüphane uygulamsı geliştirmenizi isteyeceğiz. Bu uygulama temel veritabanı işlemlerini ve Ruby on Rails' e yatkınlığınızı ölçmektedir.
Rails kurulumuna ve projeye başlamadan önce şu kaynaklardan Ruby On Rails hakkında bilgi edinmeniz gerekebilir.

* Rails Guides http://guides.rubyonrails.org/index.html
* What is gem? http://en.wikipedia.org/wiki/RubyGems

Daha sonra aşağıdaki listedeki gemleri araştırınız.

* `devise`
* `simple_form`
* `responder`
* `show_for`
* `paperclip`
* `will_paginate`
* `haml`
* `bootstrap-datepicker-rails`
* `bootstrap`


* Makinanıza Ruby On Rails' in son sürümünü kurun. Mümkünse makinanız bir linux dağıtımı olsun. Windows ortamında bu işler zor!.
* lab2023 bünyesinde geliştirdiğimiz template' i kullanarak yeni bir proje oluşturunuz. https://github.com/lab2023/rails-template. Bu template' te yukarıdaki listedeki gemler kurulu halde gelecektir.

Uygulamada; 

* Kütüphane görevlisi tarafından sisteme kitap eklenilebilecek.
* Daha sonra bu kitapların kullanıcıda mı yoksa kütüphanede mi olduğunu tutacak.

#### Projenizdeki tablolar:
##### Book
* name
* isbn
* author_id 
* is_rent (boolean)
* image

##### Author
* name

Uygulamanızı github' a push edip linkini bize gönderiniz.
Bir sonraki aşamaya geçebilirsiniz.