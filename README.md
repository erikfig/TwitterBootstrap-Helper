TwitterBootstrap-Helper
=======================

Descompact dentro da isntalação do seu Cake de forma que adicione 3 arquivos em app/View/Hekper e 1 em app/Config.

No AppController adicione:

  public $helpers = array(
    'Html' => array('className' => 'BootstrapHtml'),
    'Form' => array('className' => 'BootstrapForm'),
    'Paginator' => array('className' => 'BootstrapPaginator')
  );

De forma que fique assim:

class AppController extends Controller {
  public $helpers = array(
    'Html' => array('className' => 'BootstrapHtml'),
    'Form' => array('className' => 'BootstrapForm'),
    'Paginator' => array('className' => 'BootstrapPaginator')
  );
}

Depois pra usar fica fácil, só chamar os campos normalmente que ele cria a estrutura do HTML pro Twitter Boostrap.

Very easy...

Att. Erik
www.erikfigueiredo.com.br
