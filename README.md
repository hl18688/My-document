# Remote MongoDB and RabbitMQ Configuration

If you select the **Custom** installation type, or you are performing a SiPass integrated upgrade, the MongoDB and Rabbit Configuration dialog is displayed after entering the Username and Password for the SiPass service account. With this dialog, a remote hostname can be configured for either RabbitMQ or Mango DB, as well as Username/Password.

You can click **Next** with no changes.

- In this case, the default values (local Server name and credentials) are used
* Both RabbitMQ and MongoDB will be installed locally with the requested Username/Password
+ This will also occur automatically for the **Complete** installation type

> [!Note] 
> See the Appendix sub-section **Interval Server Ports used by Web Client** for more information on the ports used by MongoDB and RabbitMQ, along with a list of other ports used by SiPass integrated Web Client.

**In case when it is required to use the MongoDB/RabbitMQ services running somewhere else**, you can modify the Server name and Credential settings in the MongoDB and RabbitMQ Configuration dialog to ensure a successful remote connection.
> [!WARNING]
> - After installing SiPass integrated, MongoDB and RabbitMQ should be secured with the SSL communication.
> * While setting the Remote MongoDB password, user must avoid the special characters like double quotes ("), greater-than symbol (>), less -than symbol (<).
