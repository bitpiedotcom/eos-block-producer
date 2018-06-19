# EOS Block Producers for bitpie

EOS block producers in this repository may be listed in bitpie wallet. Users can create pull request to submit new block producers.

## How to submit new block producers

1. Fork this repository.
 
2. Clone your forked repository to your own computer.

3. Copy the json file `produers/template.json` to `producers/{{account_name}}.json`, and fill the template with your localized infomation.

4. A logo named `logo-{{ account_name }}.png` is required in the `images` directory. We need at least `100px x 100px` squared image.

5. Commit with comment that mentions your block producer account name, and push to your own repository.

6. Create a pull request with detailed infomation of your block producer.

7. Your pull request will be merged after we review it and everything is OK. In short time after the merge, your block producer will be listed in bitpie wallet.
