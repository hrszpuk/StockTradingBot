# Roadmap for my stock trading bot

### Overall goal
The overall goal for this project is to have a stock trading bot with a public (read-only) web interface for people to watch the bot perform.

## Milestone 1
- [ ] Python set up
- [ ] Pytest set up
- [ ] Django set up
- [ ] Obtain basic stock trading data (https://alpaca.markets/)
- [ ] Create a traditional stock market bot (non-ml)

## Milestone 2
- [ ] Create basic web interface for bot
- [ ] Create basic tests
- [ ] Set up deployment (github actions)

## Milestone 3
- [ ] Improve web interface (make it kinda like a [bloomberg terminal](https://www.gcu.ac.uk/__data/assets/image/0019/124642/Bloomberg-GettyImages-1358050858.jpg))

## Milestone 4
- [ ] Add machine learning to bot
- [ ] Machine learning model will use stock data to make decisions
- [ ] alphavantage.co has a free API for stock data
- https://github.com/pskrunner14/trading-bot

## Milestone 5
- [ ] Read financial news stories ([huggingface model for that 😉](https://huggingface.co/mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis), [another one 😌](https://huggingface.co/cometrain/stocks-news-t5/tree/main))
- [ ] Determine: companies involved, stocks involved, positive/negative
- [ ] Add companies/stocks to index and adjust investment score
- [ ] Depending on investment score buy/sell
