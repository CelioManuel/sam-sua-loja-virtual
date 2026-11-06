# SAM — Loja Virtual de Água Mineral

Aplicação de comércio electrónico orientada para telemóvel, concebida para facilitar encomendas e entregas de água mineral em Moçambique.

## Funcionalidades

- Catálogo de produtos e marcas de água.
- Carrinho, endereços, checkout e histórico de encomendas.
- Métodos de pagamento preparados para integrações M-Pesa, eMola, POS e numerário.
- Consulta do estado das entregas e visualização por mapa.
- Áreas de cliente, operador e administração.
- Interface responsiva e suporte a Android através do Capacitor.

## Tecnologias

React, TypeScript, Vite, Tailwind CSS, Supabase e Capacitor, com integração cartográfica.

## Estrutura do projecto

- `src/` — componentes, páginas, estados e integrações da interface.
- `supabase/` — funções e alterações da base de dados.
- `android/` e `ios/` — integração nativa.
- `public/` — recursos estáticos.

## Desenvolvimento

```bash
git clone https://github.com/CelioManuel/sam-sua-loja-virtual.git
cd sam-sua-loja-virtual
npm install
npm run dev
```

Para gerar a versão web: `npm run build`. Para sincronizar os recursos Android após o build: `npx cap sync android`.

## Configuração

Esta aplicação utiliza serviços externos para autenticação, pagamentos e mapas. Configure as variáveis e chaves adequadas no respectivo ambiente, sem incluir credenciais privilegiadas no repositório. Não utilize chaves de produção nos testes.

## Estado e âmbito

Código de desenvolvimento para demonstração técnica da arquitectura e dos fluxos de encomenda. Os testes de integração de pagamentos e as configurações do ambiente de produção não são cobertos por este README.

## Propriedade intelectual

O código é apresentado como projecto de desenvolvimento da plataforma SAM. Este repositório não declara uma licença de utilização pública; consulte as permissões aplicáveis antes de reutilizar código ou recursos de marca.
