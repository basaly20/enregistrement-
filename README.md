<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="Utf-8">
  <link rel="stylesheet" href="bootstrap/css/bootstrap.css">
  <link rel="stylesheet" href="bootstrap/js/bootstrap.js">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>ENREGISTREMENT</title>
</head>
<body>
    <div class="container">
        <div class="row">
            <div class=" col-md-3"></div>
                   <div class="col-md-6">
                        <h1 class="text-center">ENREGISTREMENT</h1>
                        <div class="row">
                          <label class="label col-md-3 control-label">Nom</label>
                          <div class="col-md-9">
                               <input type="text" class="form-control" name="name" placeholder="name">
                          </div>
                        </div>
                        <div class="row">
                             <label class="label col-md-3 control-label">Prenom</label>
                             <div class="col-md-9">
                                  <input type="text" class="form-control" name="prenom" placeholder="prenom">
                             </div>
                      </div>
                        <div class="row">
                         <label class="label col-md-3 control-label">Mot de passe</label>
                         <div class="col-md-9">
                              <input type="password" class="form-control" name="password" placeholder="mot de passe">
                              <small>le mot de passe doit être de 8 caractère</small>
                         </div>
                       </div>
                       <div class="row">
                         <label class="label col-md-3 control-label">Confirmation</label>
                         <div class="col-md-9">
                              <input type="text" class="form-control" name="confirmation" placeholder="confirmation">
                              </div>
                       </div>
                       <div class="row">
                         <label class="label col-md-3 control-label">MOde de paiement</label>
                         <div class="col-md-9">
                              <input type="text" class="form-control" name="paiement" placeholder="paiement">
                              </div>
                       </div>
                       <div class="row">
                         <label class="label col-md-3 control-label">E-mail</label>
                         <div class="col-md-9">
                              <input type="email" class="form-control" name="email" placeholder="email">
                              </div>
                      </div>
                               <a href="#"><div class="btn btn-info">Envoyé</div></a>
                   </div>
            </div>
            <div class="col-md-3"></div>
        </div>
    </div>
</body>
</html>
