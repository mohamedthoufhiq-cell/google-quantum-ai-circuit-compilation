# Verification and submission record

## Official task-verifier outcomes

The submitted combined archive was checked using the competition's task verifiers:

| Task | Status | Verified shots |
|---|---:|---:|
| DQI | PASS | 102,400 |
| Inverse Square Root | PASS | 200,540,928 |
| DFTHCSOS | PASS | 254,464 |

Additional reported metrics:

- **Inverse Square Root:** 260 qubits; 7,735 Toffoli gates; score 2,076,774.2337; worst error/tolerance 0.4769.
- **DFTHCSOS:** 730 qubits; 93,237 Toffoli gates; score 3,355,599,588.3155; error 1 = 0.0031852; error 2 = 0.0186396; gap-in-domain check passed.

The uploaded ZIP had 13 required files, passed the ZIP integrity test, and had no content mismatches against the source files used to construct it.

## Important distinction: experiment vs. submitted DQI file

The notebook contains an experimental DQI metadata-update patch and builds a separate file named `dqi_metadata_optimized.kmb`. However, the final packaging cell copies `sample_submission/dqi.kmb` to `/kaggle/working/submission/dqi.kmb`. The uploaded ZIP's DQI member is 886,118,180 bytes uncompressed, consistent with the large sample artifact.

Accordingly:
- The submitted DQI circuit passed the official DQI verifier.
- The metadata-update optimization is a separate experiment and should not be described as the circuit that produced the leaderboard submission.
- The experiment's notebook verifier call uses a 2,048-shot diagnostic specification; do not describe it as a full 102,400-shot verification unless a separate full run is performed on that exact experimental circuit.

## Leaderboard snapshot

On 19 November 2026, the user's screenshot showed:
- Public score: 1.00000
- Displayed position: 3367

This is a time-specific public leaderboard snapshot, not a final rank or prize result. A score of 1.00000 is the reference/baseline score.
.
