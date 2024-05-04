
# Checkout Screen

Ce widget représente l'écran de paiement d'un panier d'achats dans une application mobile. Il affiche les articles ajoutés au panier avec la possibilité de les modifier ou de les supprimer. Il affiche également le prix total et permet à l'utilisateur de procéder au paiement.

## Fonctionnalités

- Affichage des articles dans le panier avec leurs images, noms, prix et quantités.
- Possibilité de modifier ou de supprimer les articles du panier.
- Affichage du prix de base, des taxes et du prix total.
- Bouton de paiement pour procéder à la caisse.

## Captures d'écran

![Screenshot](screenshot.png)

## Utilisation

Pour utiliser ce widget, vous pouvez l'incorporer dans votre application Flutter en important le fichier `checkout7_widget.dart` et en l'appelant dans votre arborescence de widgets.

```dart
import 'checkout7_widget.dart';

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'My App',
      home: Scaffold(
        body: Checkout7Widget(),
      ),
    );
  }
}
```

## Dépendances

Ce widget utilise les dépendances suivantes :
- flutter
- provider

Pour installer ces dépendances, ajoutez les lignes suivantes à votre fichier `pubspec.yaml` :

```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^5.0.0
```

## Auteur

Ce widget a été développé parPaul-Franck Dencausse
