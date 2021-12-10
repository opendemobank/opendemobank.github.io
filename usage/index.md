# Usage manual

[Main](/)

* TOC
{:toc}

---

## Setup guide

1. Clone the repository with the following command:
    ```bash
    git clone https://github.com/opendemobank/web-client.git
    ```
2. Run the following commands in git bash, in order to update npm and install react-scripts with it:
    ```
    npm install -g npm@latest
    npm install react-scripts --save
    ```
3. You can login at [http://localhost:3000/](http://localhost:3000/) with the following credentials:

    **email:** admin@opendemobank.com

    **password:** admin

---

## Usage

### Login page

![](images/first_page.png)

The login page is located at [http://localhost:3000/](http://localhost:3000/). To continue, logging in is necessary.

**email:** admin@opendemobank.com

**password:** admin

### Account overview

![](images/accounts.png)

After logging in, the admin is directed to the admin panel.

If the admin clicks on 'create a new account', he is redirected to a new customer form.

![](images/customer-new.png)

If the admin clicks on 'make a new transfer', he is redirected to a new transfer form.

![](images/money_transfer.png)

If the admin clicks on 'invoices', he is redirected to the invoice overview page.

![](images/invoices.png)

If the admin clicks on 'account 1', he is redirected to the detailed account information.

![](images/account_detail.png)

If the admin now clicks on 'view transaction', he will see this account's transactions.

![](images/account_transactions.png)

When clicking on a specific transaction, the user will see detailed information about this transaction.

![](images/transaction_detailed.png)

[Previous (Deployment diagram)](../architecture/deployment.md)
