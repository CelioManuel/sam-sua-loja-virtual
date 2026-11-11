# Estudo de caso — SAM: experiência de encomenda de água

> Resumo técnico de um projecto público de interface e aplicações móveis. A disponibilidade em produção das integrações descritas deve ser verificada separadamente.

## Problema abordado
Simplificar encomendas de água mineral por telemóvel e organizar a experiência de clientes, operadores e administradores numa mesma solução.

## Fluxos representados no código
- Consulta do catálogo, marcas e formatos.
- Carrinho, endereço, checkout e acompanhamento de pedidos.
- Interfaces de operadores e administração.
- Componentes de localização e visualização de entregas.
- Integrações destinadas a meios de pagamento locais.
- Compatibilidade com dispositivos móveis através de Capacitor.

## Stack
- **Frontend:** React, TypeScript, Vite e Tailwind CSS.
- **Backend e dados:** Supabase e respectivas funções/migrações.
- **Mobile:** Capacitor e recursos Android/iOS.
- **Mapas:** integração cartográfica configurável.

## Decisões técnicas relevantes
1. **Aplicação mobile-first:** tornar o processo de compra utilizável num ecrã pequeno.
2. **Papéis de utilizador:** distinguir experiência do cliente, operador e administrador.
3. **Estado das encomendas:** estruturar o fluxo da submissão até ao acompanhamento.
4. **Integrações externas:** lidar com credenciais, eventos de pagamento e disponibilidade dos serviços.
5. **Distribuição móvel:** sincronizar alterações web com os projectos nativos após a compilação.

## Pontos a validar antes de produção
- Autorização de acesso aos dados e permissões no backend.
- Fluxo real dos pagamentos e tratamento de falhas.
- Sincronização das versões web e Android/iOS.
- Gestão segura de configurações e chaves.
- Testes automatizados e execução em ambiente separado.

## Explorar
- [Código fonte](../)
- [README e instruções](../README.md)

_Este estudo de caso não inclui informações de clientes, métricas internas ou configurações de produção._
