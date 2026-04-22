# Asset Flow

## Destination Technologies

<table>
	<thead>
		<tr>
			<th>Name</th>
			<th>Example(s)</th>
			<th>Platforms</th>
			<td>Assets</td>
			<th>Notes</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>BTC address</td>
			<td>
				<tt>1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa</tt>
			</td>
			<td>
				bitcoin,
				lightning,
				stacks
			</td>
			<td>
				BTC (₿)
			</td>
			<td></td>
		</tr>
		<tr>
			<td>e-mail address</td>
			<td><tt>joebloe@example.com</tt></td>
			<td>
				interact e-transfer,
				paypal
			</td>
			<td>
				<ul>
					<li>interact e-transfer:
						CAD ($)
					</li>
					<li>paypal
						AUD,
						BRL,
						CAD ($),
						CHF,
						CNY,
						CZK,
						DKK,
						GBP,
						EUR (€),
						HKD,
						HUF,
						ILS,
						JPY,
						MYR,
						MXN,
						NOK,
						NZD,
						PHP,
						PLN,
						SEK,
						SGD,
						THB,
						TWD,
						USD
					</li>
				</ul>
			</td>
			<td></td>
		</tr>
		<tr>
			<td>EVM address</td>
			<td><tt>0x00000000219ab540356cBB839Cbe05303d7705Fa</tt></td>
			<td>
				arbitrum,
				avalanche,
				base,
				berachain,
				ethereum,
				fantom,
				monad,
				optimism,
				polygon,
				sei,
				<em>etc</em>.
			</td>
			<td>
				AVAX,
				BERA,
				ETH,
				FTM,
				MATIC,
				MON,
				SEI,
				<em>etc</em>.
			</td>
			<td></td>
		</tr>
		<tr>
			<td>IBAN (International Bank Account Number)</td>
			<td>
				<ul>
					<li>DE75 5121 0800 1245 1261 99</li>
					<li>GB33 BUKB 2020 1555 5555 55</li>
					<li>FR76 3000 6000 0112 3456 7890 189</li>
					<li>NL02 ABNA 0123 4567 89</li>
					<li>IT60 X054 2811 1010 0000 0123 456</li>
					<li>CH56 0483 5012 3456 7800 9</li>
				</ul>
			</td>
			<td>SEPA</td>
			<td>
				EURO (€)
			</td>
			<td>
				Not just for Europe; over 70 countries worldwide including the UAE, Brazil, and many African nations.
				The USA and Canada, however, do not use IBANs.
			</td>
		</tr>
		<tr>
			<td>payment pointer</td>
			<td>
				<ul>
					<li><tt>$example.com</tt></li>
					<li><tt>$joeblow.example.com</tt></li>
					<li><tt>$example.com/janedoe</tt></li>
				</ul>
			</td>
			<td>
				interledger
			</td>
			<td></td>
			<td></td>
		</tr>
		<tr>
			<td>Marriott Bonvoy loyalty program 9-digit ID</td>
			<td>
				<tt>123 456 789</tt>
			</td>
			<td>Marriott Bonvoy</td>
			<td>
				Marriott Bonvoy loyalty points
			</td>
			<td></td>
		</tr>
		<tr>
			<td>payto URI scheme</td>
			<td>
				<ul>
					<li>
						<tt>payto:sepa/DE12345678901234567890</tt> (SEPA (IBAN))
					</li>
					<li>
						<tt>payto:bitcoin/1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa</tt> (BTC)
					</li>
					<li>
						<tt>payto:interac/recipient@example.com</tt> (Interac E-Transfer E-Mail Address)
					</li>
					<li>
						<tt>payto:ach/123456789/987654321</tt> (ACH (USA))
					</li>
				</ul>
			</td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>


## Source Technologies
