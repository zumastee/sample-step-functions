# AWS Step Functions Sample

A sample project demonstrating AWS Step Functions state machines.

## Project Structure

```
sample-step-functions/
├── statemachines/
│   └── hello-world.asl.json    # Hello World state machine
└── README.md
```

## State Machine Description

### Hello World State Machine

A simple example using the Pass state to demonstrate basic Step Functions functionality.

#### State Machine Configuration

- Start State: `Pass`
- End State: `Pass`
- Output: `{"result": "Hello"}`

#### Execution Result

```json
{
  "result": "Hello"
}
```

## Usage

1. Access the AWS Step Functions console
2. Select "Create state machine"
3. Copy and paste the contents of `hello-world.asl.json`
4. Execute the state machine

## Development Environment Setup

1. Install AWS CLI
2. Configure AWS credentials
3. Verify AWS Step Functions access permissions

## Notes

- This sample demonstrates basic usage of the Pass state
- You can build more complex state machines based on your actual use cases
- It is recommended to delete unused state machines for cost optimization 