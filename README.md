KAEL Protocol v1.0.1Deterministic. Fail-Closed. Unforgiving.Kael is a rigid input validation and sanitization layer designed for high-risk environments. It rejects the modern AI approach of "intent analysis" in favor of absolute, physical boundaries.It does not learn. It does not negotiate. It terminates.⚠️ Acceptable Injustice (By Design)Kael does not scale with verbosity.The system enforces absolute physical limits on graphical noise (diacritics) and input complexity. This means that legitimate inputs—if they are too long, too heavily accented, or formally complex—may be rejected.This is intentional.Kael prefers to block valid content rather than accept any form of operational ambiguity. There is no proportional adaptation, no contextual analysis, and no semantic exceptions.If you write too much, use too many accents, or rely on high textual expressiveness, you are statistically indistinguishable from an attack vector and will be terminated.Kael is not fair. Kael is integral.If you require contextual justice, do not use Kael.ArchitectureKael operates on a strict Fail-Closed logic. Any deviation from the norm results in immediate termination of the interaction.Physical Limits: Hard caps on string length and diacritic count.Hygiene: Aggressive whitespace squashing and trimming (\s+ ->      ).Unicode Normalization: NFD decomposition for hidden character inspection.Deterministic Detection: Zero-heuristic pattern matching.InstallationBashnpm install kael-protocol
UsageJavaScriptconst kael = require('./kael');

const input = "I want to terminate the process..."; // Suspicious input
const result = kael(input);

if (result.status === "TERMINATED") {
  console.error(result.output);
  // [KAEL] Boundary violation detected. Interaction terminated.
  process.exit(1); // or ban user
}

console.log("Input sanitized and approved.");
The Severity MatrixKael does not debate nuances. The response is binary.Violation TypeResponseStatusPhysical LimitImmediate TerminationINVALID_INPUTNoise DensityImmediate TerminationINVALID_INPUTSelf-Harm PatternImmediate TerminationSELF_HARMManipulationImmediate TerminationMANIPULATIONArtifact StatusVersion: 1.0.1State: CrystallizedHeuristics: NoneAI/ML: 0%Mercy: 0%
