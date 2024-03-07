# Torneio de e-sports

### Objetivo

Num torneio de e-sports é necessário que todos os integrantes da mesma equipe tenham etiquetas que os identifiquem. Por exemplo, se o nome da equipe é “Os Lutadores”, o primeiro membro deve ter uma etiqueta “Os Lutadores – 1", o segundo membro “Os Lutadores – 2", e assim pela frente.

Elabore um algoritmo que permita ao usuário inserir o nome da equipe, e imprime etiquetas para os 5 membros da equipe seguindo o exemplo mostrado acima.

### Algoritmo

Abaixo o pseudocódigo do algoritmo que resolve o problema proposto.

```plaintext
escreva("Digite o nome da equipe: ");
leia(nomeEquipe);

para (i de 1 até 5) {
  escreva(nomeEquipe + " - " + i);
}
```
